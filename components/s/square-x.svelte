<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr-j4s5gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr-j4s5gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-x" {...props}></Icon>
