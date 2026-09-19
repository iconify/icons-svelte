<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgsnhxbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":432};
const content = `<path class="sgsnhxbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:youtube" {...props}></Icon>
