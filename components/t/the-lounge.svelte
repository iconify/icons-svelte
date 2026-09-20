<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o84xpx01m.css';
import '../../css/u/ugibgdcyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o84xpx01m"/><path class="ugibgdcyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-lounge" {...props}></Icon>
