<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhwaf8bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwaf8bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tag-x" {...props}></Icon>
