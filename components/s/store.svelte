<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqkwkbbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fqkwkbbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:store" {...props}></Icon>
