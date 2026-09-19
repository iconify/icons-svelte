<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2f7wub-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="t2f7wub-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:unity" {...props}></Icon>
