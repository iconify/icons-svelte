<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1e-qzb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1e-qzb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-low" {...props}></Icon>
