<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvkn6fpfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvkn6fpfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:skull" {...props}></Icon>
