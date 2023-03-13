<?xml version="1.0" encoding="UTF-8"?>
<ui version="4.0">
 <class>MainWindow</class>
 <widget class="QMainWindow" name="MainWindow">
  <property name="geometry">
   <rect>
    <x>0</x>
    <y>0</y>
    <width>847</width>
    <height>740</height>
   </rect>
  </property>
  <property name="windowTitle">
   <string>Hoşgeldiniz</string>
  </property>
  <widget class="QWidget" name="centralwidget">
   <widget class="QLabel" name="label">
    <property name="geometry">
     <rect>
      <x>-10</x>
      <y>-10</y>
      <width>861</width>
      <height>671</height>
     </rect>
    </property>
    <property name="minimumSize">
     <size>
      <width>861</width>
      <height>671</height>
     </size>
    </property>
    <property name="maximumSize">
     <size>
      <width>861</width>
      <height>671</height>
     </size>
    </property>
    <property name="lineWidth">
     <number>2</number>
    </property>
    <property name="text">
     <string/>
    </property>
    <property name="pixmap">
     <pixmap>EARTH in 8K ULTRA HD - Tour Through the Planet Earth - Best Places and Animals Relaxing Music 8K TV - YouTube - Google Chrome 20.02.2022 18_01_05.png</pixmap>
    </property>
   </widget>
   <widget class="QLabel" name="label_2">
    <property name="geometry">
     <rect>
      <x>270</x>
      <y>0</y>
      <width>371</width>
      <height>41</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <family>Bahnschrift SemiLight</family>
      <pointsize>20</pointsize>
     </font>
    </property>
    <property name="styleSheet">
     <string notr="true">color: rgb(46, 0, 140);</string>
    </property>
    <property name="text">
     <string>   ÖĞRENCİ KAYIT SİSTEMİ</string>
    </property>
   </widget>
   <widget class="QLabel" name="Ad">
    <property name="geometry">
     <rect>
      <x>40</x>
      <y>70</y>
      <width>81</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
     </font>
    </property>
    <property name="text">
     <string>Ad:</string>
    </property>
   </widget>
   <widget class="QLabel" name="Soyad">
    <property name="geometry">
     <rect>
      <x>40</x>
      <y>100</y>
      <width>81</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
     </font>
    </property>
    <property name="text">
     <string>Soyad:</string>
    </property>
   </widget>
   <widget class="QLabel" name="TcNo">
    <property name="geometry">
     <rect>
      <x>40</x>
      <y>130</y>
      <width>81</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
     </font>
    </property>
    <property name="text">
     <string>Tc No:</string>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit">
    <property name="geometry">
     <rect>
      <x>110</x>
      <y>70</y>
      <width>133</width>
      <height>22</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>10</pointsize>
     </font>
    </property>
    <property name="text">
     <string/>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit_2">
    <property name="geometry">
     <rect>
      <x>110</x>
      <y>130</y>
      <width>133</width>
      <height>22</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>10</pointsize>
     </font>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit_3">
    <property name="geometry">
     <rect>
      <x>110</x>
      <y>100</y>
      <width>133</width>
      <height>22</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>10</pointsize>
     </font>
    </property>
   </widget>
   <widget class="QFrame" name="frame">
    <property name="geometry">
     <rect>
      <x>80</x>
      <y>190</y>
      <width>171</width>
      <height>71</height>
     </rect>
    </property>
    <property name="frameShape">
     <enum>QFrame::Box</enum>
    </property>
    <property name="frameShadow">
     <enum>QFrame::Raised</enum>
    </property>
    <widget class="QLabel" name="label_3">
     <property name="geometry">
      <rect>
       <x>50</x>
       <y>10</y>
       <width>91</width>
       <height>16</height>
      </rect>
     </property>
     <property name="font">
      <font>
       <family>Bahnschrift SemiLight</family>
       <pointsize>12</pointsize>
       <weight>50</weight>
       <bold>false</bold>
      </font>
     </property>
     <property name="text">
      <string>Bölümü:</string>
     </property>
    </widget>
    <widget class="QComboBox" name="bolumu">
     <property name="geometry">
      <rect>
       <x>18</x>
       <y>40</y>
       <width>141</width>
       <height>22</height>
      </rect>
     </property>
     <property name="font">
      <font>
       <pointsize>10</pointsize>
      </font>
     </property>
    </widget>
   </widget>
   <widget class="QLabel" name="label_4">
    <property name="geometry">
     <rect>
      <x>290</x>
      <y>70</y>
      <width>141</width>
      <height>21</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <family>Bahnschrift SemiLight</family>
      <pointsize>12</pointsize>
      <weight>50</weight>
      <bold>false</bold>
     </font>
    </property>
    <property name="text">
     <string>Doğum Tarihi:</string>
    </property>
   </widget>
   <widget class="QCalendarWidget" name="Dogumtarihi">
    <property name="geometry">
     <rect>
      <x>290</x>
      <y>100</y>
      <width>311</width>
      <height>161</height>
     </rect>
    </property>
   </widget>
   <widget class="QTableWidget" name="tablo">
    <property name="geometry">
     <rect>
      <x>-5</x>
      <y>380</y>
      <width>891</width>
      <height>361</height>
     </rect>
    </property>
    <property name="rowCount">
     <number>20</number>
    </property>
    <property name="columnCount">
     <number>5</number>
    </property>
    <attribute name="horizontalHeaderDefaultSectionSize">
     <number>167</number>
    </attribute>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <row/>
    <column>
     <property name="text">
      <string>Ad</string>
     </property>
    </column>
    <column>
     <property name="text">
      <string>Soyad</string>
     </property>
    </column>
    <column>
     <property name="text">
      <string>Tc No</string>
     </property>
    </column>
    <column>
     <property name="text">
      <string>Bölümü</string>
     </property>
    </column>
    <column>
     <property name="text">
      <string>Doğum Tarihi</string>
     </property>
    </column>
   </widget>
   <widget class="QPushButton" name="kayitekle">
    <property name="geometry">
     <rect>
      <x>160</x>
      <y>330</y>
      <width>201</width>
      <height>23</height>
     </rect>
    </property>
    <property name="text">
     <string>Kayıt Ekle</string>
    </property>
   </widget>
   <widget class="QPushButton" name="kayitsil">
    <property name="geometry">
     <rect>
      <x>470</x>
      <y>330</y>
      <width>201</width>
      <height>23</height>
     </rect>
    </property>
    <property name="text">
     <string>Kayıt Sil</string>
    </property>
   </widget>
  </widget>
 </widget>
 <resources/>
 <connections/>
</ui>
