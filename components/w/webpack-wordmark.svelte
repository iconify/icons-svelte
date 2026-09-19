<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vv6pb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p9vv6pb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:webpack-wordmark" {...props}></Icon>
