<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucq63j0-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucq63j0-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-arrow-right" {...props}></Icon>
