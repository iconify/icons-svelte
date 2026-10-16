<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pec648bzl.css';
import '../../css/i/i4lld7tyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pec648bzl"/><path class="i4lld7tyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rupee-20" {...props}></Icon>
