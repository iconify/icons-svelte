<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exs0fwbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exs0fwbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-vertical-1-round" {...props}></Icon>
