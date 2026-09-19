<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f89z9b01p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f89z9b01p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:viaf" {...props}></Icon>
