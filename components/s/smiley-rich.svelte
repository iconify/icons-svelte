<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otnv16btc.css';
import '../../css/a/aagla3kgr.css';
import '../../css/m/mmkzhsffi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otnv16btc"/><path class="aagla3kgr"/><path class="mmkzhsffi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-rich" {...props}></Icon>
