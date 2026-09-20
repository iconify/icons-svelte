<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kijpecbmw.css';
import '../../css/c/c-2glzb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kijpecbmw"/><path class="c-2glzb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:send-line" {...props}></Icon>
