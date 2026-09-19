<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v19ilacll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v19ilacll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:squares-plus-16-solid" {...props}></Icon>
