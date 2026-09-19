<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1-2btbhm.css';
import '../../css/h/hkl-kbbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1-2btbhm"/><path class="hkl-kbbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:ruler" {...props}></Icon>
