<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azuihx65x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="azuihx65x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:text-decoration" {...props}></Icon>
