<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plii2cbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plii2cbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shift" {...props}></Icon>
