<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukh7dc-hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ukh7dc-hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitter" {...props}></Icon>
