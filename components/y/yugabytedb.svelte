<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faafu0brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="faafu0brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yugabytedb" {...props}></Icon>
