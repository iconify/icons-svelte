<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7di7ab6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z7di7ab6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:square-full" {...props}></Icon>
