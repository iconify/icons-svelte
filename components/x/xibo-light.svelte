<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/his-o6bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="his-o6bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xibo-light" {...props}></Icon>
