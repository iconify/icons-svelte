<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3nm04bma.css';
import '../../css/k/khhbi52zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3nm04bma"/><path class="khhbi52zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:swatch-16-solid" {...props}></Icon>
