<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw654hwgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw654hwgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shopping-bag-1-line" {...props}></Icon>
