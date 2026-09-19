<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km9et_bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="km9et_bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sort-up-alt" {...props}></Icon>
