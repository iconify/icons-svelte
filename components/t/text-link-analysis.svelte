<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5zc53bhn.css';
import '../../css/o/otd0eoc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k5zc53bhn"/><path class="otd0eoc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-link-analysis" {...props}></Icon>
