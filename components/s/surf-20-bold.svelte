<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4rw3bb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s4rw3bb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:surf-20-bold" {...props}></Icon>
