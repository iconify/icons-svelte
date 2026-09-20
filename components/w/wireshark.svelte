<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4b7g0lxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4b7g0lxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wireshark" {...props}></Icon>
