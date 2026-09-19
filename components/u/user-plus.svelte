<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckiq7ve7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ckiq7ve7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-plus" {...props}></Icon>
