<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tosodm3wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tosodm3wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:x-circle-20-solid" {...props}></Icon>
