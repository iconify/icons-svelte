<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afqxesbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afqxesbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virola-light" {...props}></Icon>
