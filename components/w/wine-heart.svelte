<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7icocbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7icocbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wine-heart" {...props}></Icon>
