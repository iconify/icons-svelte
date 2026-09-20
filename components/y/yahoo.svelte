<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3vfzo9us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3vfzo9us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:yahoo" {...props}></Icon>
