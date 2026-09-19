<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdfm2xl6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kdfm2xl6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sun-20-solid" {...props}></Icon>
