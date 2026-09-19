<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjxrthbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qjxrthbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:suit-heart-fill" {...props}></Icon>
