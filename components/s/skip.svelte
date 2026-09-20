<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd58tpebb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd58tpebb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip" {...props}></Icon>
