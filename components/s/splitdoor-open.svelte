<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yee79pbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yee79pbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:splitdoor-open" {...props}></Icon>
