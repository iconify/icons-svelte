<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlyr80z1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlyr80z1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:v0" {...props}></Icon>
