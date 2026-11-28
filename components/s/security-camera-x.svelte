<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g91jwbbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g91jwbbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:security-camera-x" {...props}></Icon>
