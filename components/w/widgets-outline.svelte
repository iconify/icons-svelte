<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwp63zbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwp63zbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widgets-outline" {...props}></Icon>
