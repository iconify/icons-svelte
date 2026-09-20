<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl-ijsbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-ijsbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-none-line" {...props}></Icon>
