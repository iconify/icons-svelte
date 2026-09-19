<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3tc6s50q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m3tc6s50q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:scale-16-solid" {...props}></Icon>
