<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jog7wibwp.css';
import '../../css/w/wx_6pkbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jog7wibwp"/><path class="wx_6pkbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-square" {...props}></Icon>
