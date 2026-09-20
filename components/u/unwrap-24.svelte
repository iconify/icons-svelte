<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p392hibyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p392hibyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unwrap-24" {...props}></Icon>
