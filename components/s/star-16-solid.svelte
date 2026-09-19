<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7hr3-2pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h7hr3-2pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:star-16-solid" {...props}></Icon>
