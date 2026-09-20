<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9z0pybyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9z0pybyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:worklenz-light" {...props}></Icon>
