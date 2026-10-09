<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jocetjbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jocetjbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semicircle-20-bold" {...props}></Icon>
