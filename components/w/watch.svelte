<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r82rz7l0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r82rz7l0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:watch" {...props}></Icon>
