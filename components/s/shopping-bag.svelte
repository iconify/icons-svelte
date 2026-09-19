<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eis0ofcwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eis0ofcwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:shopping-bag" {...props}></Icon>
