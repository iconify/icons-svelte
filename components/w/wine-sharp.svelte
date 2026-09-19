<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifyke3bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ifyke3bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wine-sharp" {...props}></Icon>
