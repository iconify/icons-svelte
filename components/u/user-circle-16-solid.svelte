<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7r4tcwgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7r4tcwgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-circle-16-solid" {...props}></Icon>
