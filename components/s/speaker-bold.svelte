<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylytocbab.css';
import '../../css/y/yqbs--b0w.css';
import '../../css/g/gcio5b78g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylytocbab"/><path class="yqbs--b0w"/><path clip-rule="evenodd" class="gcio5b78g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:speaker-bold" {...props}></Icon>
