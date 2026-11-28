<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhjtteayv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhjtteayv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sheep-solid" {...props}></Icon>
