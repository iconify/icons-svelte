<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jirkywbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jirkywbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:weight-scale" {...props}></Icon>
