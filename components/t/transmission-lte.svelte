<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvmivbb5a.css';
import '../../css/i/ih5xe3bid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cvmivbb5a"/><path class="ih5xe3bid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:transmission-lte" {...props}></Icon>
