<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxpqymarw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxpqymarw primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vector-skew-duotone" {...props}></Icon>
