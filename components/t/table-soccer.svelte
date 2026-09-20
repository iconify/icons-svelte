<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd9p4freu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pd9p4freu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:table-soccer" {...props}></Icon>
