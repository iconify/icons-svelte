<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drvk6ud3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drvk6ud3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uncloud-light" {...props}></Icon>
