<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl93hlkdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl93hlkdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-edit" {...props}></Icon>
