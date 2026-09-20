<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq9fdxb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zq9fdxb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:ruler-square" {...props}></Icon>
