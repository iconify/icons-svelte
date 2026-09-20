<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0f5rt5bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0f5rt5bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:style-outline" {...props}></Icon>
