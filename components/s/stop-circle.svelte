<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn1uib6zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn1uib6zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stop-circle" {...props}></Icon>
