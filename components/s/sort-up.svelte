<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cunm7x32u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cunm7x32u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:sort-up" {...props}></Icon>
