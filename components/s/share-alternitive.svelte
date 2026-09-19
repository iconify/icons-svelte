<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmwflr6ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dmwflr6ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:share-alternitive" {...props}></Icon>
