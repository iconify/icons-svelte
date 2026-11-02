<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snbezvl1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snbezvl1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-none-line" {...props}></Icon>
