<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnih7ubew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pnih7ubew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:trending-down" {...props}></Icon>
