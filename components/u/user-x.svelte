<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtz98abol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtz98abol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-x" {...props}></Icon>
