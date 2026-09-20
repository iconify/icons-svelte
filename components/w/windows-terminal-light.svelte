<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj9b7k8db.css';
import '../../css/y/ym98bkbma.css';
import '../../css/y/yy5qrkvzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jj9b7k8db"/><path class="ym98bkbma"/><path class="yy5qrkvzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windows-terminal-light" {...props}></Icon>
