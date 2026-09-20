<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tup0qkl1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tup0qkl1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:trophy-24" {...props}></Icon>
