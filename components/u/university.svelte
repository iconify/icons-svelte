<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-koukvr.css';
import '../../css/n/n11wxrbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ey-koukvr"/><path class="n11wxrbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:university" {...props}></Icon>
