<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg_xf-bjm.css';
import '../../css/s/stheyzbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bg_xf-bjm"/><path class="stheyzbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:version-minor" {...props}></Icon>
