<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7c9n1blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1085,"height":614};
const content = `<path class="p7c9n1blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:soundcloud" {...props}></Icon>
