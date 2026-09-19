<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ontx3kbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ontx3kbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:usb" {...props}></Icon>
