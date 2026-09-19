<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgki4y25j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="mgki4y25j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-package" {...props}></Icon>
