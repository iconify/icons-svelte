<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f398k2a7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f398k2a7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:zoo" {...props}></Icon>
