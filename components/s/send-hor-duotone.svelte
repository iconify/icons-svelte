<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ezlsbrm.css';
import '../../css/l/lxlb-0bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ezlsbrm"/><path class="lxlb-0bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-hor-duotone" {...props}></Icon>
