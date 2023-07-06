Aplikasi management Hutang & Piutang support report PDF

## Tech Stack

**Client:** Flutter

**Architecture** MVVM

**State Management** Riverpod

## Installation

1. `flutter clean && flutter pub get`
2. `dart run build_runner watch --delete-conflicting-outputs`
3. `flutter run`

## Feature

- [x] Management People (Read, Update, Delete, Add)
- [x] Management Transaction (Create, Update, Read)
- [x] Management Payment (Create, Update, Delete, Add)
- [x] Print Report PDF
      a. Based on people
      b. All transaction
      c. Specific Transaction

## Screenshot

### People List

<table>
    <tbody>
        <tr>
            <td align="center" style="font-weight:bold;">Home</td>
            <td align="center" style="font-weight:bold;">List People</td>
            <td align="center" style="font-weight:bold;">List Transaction</td>
        </tr>
        <tr>
            <td align="center">
                <img src="assets/screenshot/3.home.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/1.people-list.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/2.transaction-list.png" height="400"/>
            </td>
        </tr>
        <!-- New Row -->
        <tr>
            <td align="center" style="font-weight:bold;">Transaction People</td>
            <td align="center" style="font-weight:bold;">Detail Transaction</td>
            <td align="center" style="font-weight:bold;">Report PDF</td>
        </tr>
        <tr>
            <td align="center">
                <img src="assets/screenshot/4.transaction-by-people.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/5.detail-transaction.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/6.print-report-pdf.png" height="400"/>
            </td>
        </tr>
         <!-- New Row -->
        <tr>
            <td align="center" style="font-weight:bold;">PDF Result</td>
            <td align="center" style="font-weight:bold;">Export JSON</td>
            <td align="center" style="font-weight:bold;">Import JSON</td>
        </tr>
        <tr>
            <td align="center">
                <img src="assets/screenshot/7.pdf-result.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/8.export.png" height="400"/>
            </td>
            <td align="center">
                <img src="assets/screenshot/9.import.png" height="400"/>
            </td>
        </tr>
    </tbody>
</table>
