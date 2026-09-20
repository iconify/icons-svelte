<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krsjxac7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="krsjxac7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sync-16" {...props}></Icon>
