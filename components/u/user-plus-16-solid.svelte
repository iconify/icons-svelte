<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqvpuqhiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cqvpuqhiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-plus-16-solid" {...props}></Icon>
