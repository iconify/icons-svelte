<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry4ptt9wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ry4ptt9wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:scale-20-solid" {...props}></Icon>
