<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_crnsbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="a_crnsbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-circle" {...props}></Icon>
