<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7i_kf9pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="i7i_kf9pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:video-slash" {...props}></Icon>
