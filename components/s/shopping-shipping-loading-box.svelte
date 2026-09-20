<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebc7d1mqz.css';
import '../../css/j/j4kat4bzg.css';
import '../../css/o/oh9bdxpde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ebc7d1mqz"/><path class="j4kat4bzg"/><path class="oh9bdxpde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-loading-box" {...props}></Icon>
