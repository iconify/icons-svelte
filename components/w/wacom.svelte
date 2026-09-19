<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0bm4bcod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z0bm4bcod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wacom" {...props}></Icon>
