<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhi3h8bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="fhi3h8bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shovel" {...props}></Icon>
