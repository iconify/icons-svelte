<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3r_b-b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3r_b-b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wintertrace-light" {...props}></Icon>
