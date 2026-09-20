<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9j7h1rxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="z9j7h1rxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sort-amount-dsc" {...props}></Icon>
