<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hptyw3s8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hptyw3s8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:sun-16-solid" {...props}></Icon>
