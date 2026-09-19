<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3si62x3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":551,"height":717};
const content = `<path class="f3si62x3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:unlock" {...props}></Icon>
