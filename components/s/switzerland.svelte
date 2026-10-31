<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wta7eoblc.css';
import '../../css/y/ywgw6ib8n.css';
import '../../css/o/o5mwc3v0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wta7eoblc"/><path class="ywgw6ib8n"/><path class="o5mwc3v0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:switzerland" {...props}></Icon>
