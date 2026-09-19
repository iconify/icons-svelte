<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-0lb3bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="p-0lb3bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:toilet-paper-slash" {...props}></Icon>
