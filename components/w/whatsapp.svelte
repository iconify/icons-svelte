<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiec4kn4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oiec4kn4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:whatsapp" {...props}></Icon>
