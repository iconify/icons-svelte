<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkde0b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="glkde0b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:signs-post-2" {...props}></Icon>
