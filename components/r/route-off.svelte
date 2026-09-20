<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upkk8ccad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upkk8ccad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:route-off" {...props}></Icon>
