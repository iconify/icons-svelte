<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptc16vbmh.css';
import '../../css/p/pvum3qbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptc16vbmh"/><path class="pvum3qbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:surprised-filled" {...props}></Icon>
