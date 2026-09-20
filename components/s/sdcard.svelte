<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzukqibls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hzukqibls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sdcard" {...props}></Icon>
