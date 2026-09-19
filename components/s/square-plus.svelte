<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd2k8rb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gd2k8rb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-plus" {...props}></Icon>
