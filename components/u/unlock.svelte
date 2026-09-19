<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_droebqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w_droebqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:unlock" {...props}></Icon>
