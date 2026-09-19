<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzskvyx6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rzskvyx6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:sign-out" {...props}></Icon>
