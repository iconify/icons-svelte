<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5vr4bbia.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hqm2qbcec.css';
import '../../css/j/jjvyhvb4o.css';
import '../../css/b/botn2_sad.css';
import '../../css/z/zhdj_yccb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w5vr4bbia"/><g class="dt0cm9dhy primary"><path class="hqm2qbcec"/><path class="jjvyhvb4o"/><path class="botn2_sad"/><path class="zhdj_yccb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:share-duo" {...props}></Icon>
