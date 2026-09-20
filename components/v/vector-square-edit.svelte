<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p099_modx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p099_modx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-square-edit" {...props}></Icon>
