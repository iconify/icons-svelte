<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb-4ft_ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-4ft_ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-bezier" {...props}></Icon>
