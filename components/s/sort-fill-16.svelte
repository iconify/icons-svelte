<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yocna9rlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yocna9rlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sort-fill-16" {...props}></Icon>
