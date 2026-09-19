<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v63_47ots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="v63_47ots"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:viruses" {...props}></Icon>
