<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyx_jbcae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyx_jbcae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:street-view" {...props}></Icon>
