<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygxidybwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ygxidybwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-bold" {...props}></Icon>
