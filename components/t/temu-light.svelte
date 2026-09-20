<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsr4uac1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nsr4uac1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temu-light" {...props}></Icon>
