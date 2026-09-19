<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2qjncbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":512};
const content = `<path class="n2qjncbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tablet-mac" {...props}></Icon>
