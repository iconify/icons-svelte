<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwy3jw9qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zwy3jw9qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-dim-20-bold" {...props}></Icon>
