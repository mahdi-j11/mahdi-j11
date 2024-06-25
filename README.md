<?xml version="1.0" encoding="UTF-8"?>
<mxfile host="app.diagrams.net">
  <diagram name="Activity Diagram">
    <mxGraphModel dx="738" dy="485" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- Swimlanes -->
        <mxCell id="2" value="משתמש" style="swimlane;childLayout=stackLayout;horizontal=1;startSize=20;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="0" y="0" width="200" height="800" as="geometry"/>
        </mxCell>
        <mxCell id="3" value="מערכת" style="swimlane;childLayout=stackLayout;horizontal=1;startSize=20;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="200" y="0" width="200" height="800" as="geometry"/>
        </mxCell>

        <!-- User Actions -->
        <mxCell id="4" value="Start" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="2">
          <mxGeometry x="80" y="60" width="40" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="5" value="משתמש צופה במפת רכיבי ההשקיה" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="2">
          <mxGeometry x="40" y="120" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="6" value="משתמש בוחר רכיב מסוים" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="2">
          <mxGeometry x="40" y="180" width="120" height="40" as="geometry"/>
        </mxCell>

        <!-- System Actions -->
        <mxCell id="7" value="המערכת מציגה נתונים חיים" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="60" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="8" value="האם זוהתה בעיה?" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="80" y="120" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="9" value="המערכת מתריעה על בעיה" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="180" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="10" value="החיישן הבעייתי מהבהב" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="240" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="11" value="המערכת טוענת נתונים עבור הרכיב שנבחר" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="300" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="12" value="האם המערכת הצליחה לטעון את הנתונים?" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="80" y="360" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="13" value="הצגת נתונים" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="420" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="14" value="ניסיון לטעון נתונים מחדש (עד 3 פעמים)" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="480" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="15" value="האם מספר הניסיונות < 3?" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="80" y="540" width="80" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="16" value="המערכת מציגה הודעת שגיאה" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="40" y="600" width="120" height="40" as="geometry"/>
        </mxCell>
        <mxCell id="17" value="End" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="3">
          <mxGeometry x="80" y="660" width="40" height="40" as="geometry"/>
        </mxCell>

        <!-- Connections -->
        <mxCell id="18" edge="1" parent="2" source="4" target="5">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="19" edge="1" parent="2" source="5" target="6">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="20" edge="1" parent="3" source="6" target="7">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="21" edge="1" parent="3" source="7" target="8">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="22" edge="1" parent="3" source="8" target="9">
          <mxGeometry relative="1" as="geometry"/>
          <mxPoint x="120" y="120" as="sourcePoint"/>
          <mxPoint x="120" y="180" as="targetPoint"/>
        </mxCell>
        <mxCell id="23" edge="1" parent="3" source="8" target="11">
          <mxGeometry relative="1" as="geometry"/>
          <mxPoint x="120" y="120" as="sourcePoint"/>
          <mxPoint x="120" y="300" as="targetPoint"/>
        </mxCell>
        <mxCell id="24" edge="1" parent="3" source="9" target="10">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="25" edge="1" parent="3" source="11" target="12">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="26" edge="1" parent="3" source="12" target="13">
          <mxGeometry relative="1" as="geometry"/>
          <mxPoint x="120" y="360" as="sourcePoint"/>
          <mxPoint x="120" y="420" as="targetPoint"/>
        </mxCell>
        <mxCell id="27" edge="1" parent="3" source="12" target="14">
          <mxGeometry relative="1" as="geometry"/>
          <mxPoint x="120" y="360" as="sourcePoint"/>
          <mxPoint x="120" y="480" as="targetPoint"/>
        </mxCell>
        <mxCell id="28" edge="1" parent="3" source="14" target="15">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="29" edge="1" parent="3" source="15" target="11">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="30" edge="1" parent="3" source="15" target="16">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="31" edge="1" parent="3" source="13" target="17">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="32" edge="1" parent="3" source="16" target="17">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
