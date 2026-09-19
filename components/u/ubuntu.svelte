<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtly1zbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":702,"height":704};
const content = `<path class="gtly1zbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ubuntu" {...props}></Icon>
