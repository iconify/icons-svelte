<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c76bwnbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c76bwnbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:signal-1" {...props}></Icon>
