<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i29v76buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i29v76buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-minus-16-solid" {...props}></Icon>
