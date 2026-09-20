<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtwn89bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qtwn89bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-silence-outline" {...props}></Icon>
