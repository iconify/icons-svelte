<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acd90xb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="acd90xb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sign-hanging" {...props}></Icon>
