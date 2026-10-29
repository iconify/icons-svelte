<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e1_l5ubsi.css';
import '../../css/k/kf39h1bgu.css';
import '../../css/e/ex4tq7bmu.css';
import '../../css/m/m0mdqxbos.css';
import '../../css/v/v8fmq4b1i.css';
import '../../css/x/xoixuo9hi.css';
import '../../css/h/hody_vbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e1_l5ubsi"/><path class="kf39h1bgu wm-k"/><path class="ex4tq7bmu wm-a"/><path class="m0mdqxbos wm-s"/><path class="v8fmq4b1i wm-s"/><path class="wm-s xoixuo9hi"/><path class="hody_vbyh wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sparkler-sketch" {...props}></Icon>
