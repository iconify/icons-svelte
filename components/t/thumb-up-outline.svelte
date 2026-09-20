<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feyrttbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="feyrttbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:thumb-up-outline" {...props}></Icon>
