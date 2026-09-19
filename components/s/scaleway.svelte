<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma23w-rvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ma23w-rvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:scaleway" {...props}></Icon>
