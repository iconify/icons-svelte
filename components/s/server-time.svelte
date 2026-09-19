<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okximigwt.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/a/avvjpobem.css';
import '../../css/c/cr9nds-9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="okximigwt"/><circle class="dlp7nstpk"/><path class="avvjpobem"/><path class="cr9nds-9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:server-time" {...props}></Icon>
