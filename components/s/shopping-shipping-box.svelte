<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecr8r-six.css';
import '../../css/i/ibldiexph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ecr8r-six"/><path class="ibldiexph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-box" {...props}></Icon>
