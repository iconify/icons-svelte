<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9n0nyb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9n0nyb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:trophy" {...props}></Icon>
