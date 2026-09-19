<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvjya4bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvjya4bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:timer-off" {...props}></Icon>
