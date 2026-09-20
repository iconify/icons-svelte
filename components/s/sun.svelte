<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/der0l86hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="der0l86hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sun" {...props}></Icon>
