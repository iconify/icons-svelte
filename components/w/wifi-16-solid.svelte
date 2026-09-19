<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk3daea8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yk3daea8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wifi-16-solid" {...props}></Icon>
