<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivb83k4ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivb83k4ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wind-energy-alt" {...props}></Icon>
