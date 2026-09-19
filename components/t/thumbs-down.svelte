<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kilwro9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kilwro9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thumbs-down" {...props}></Icon>
