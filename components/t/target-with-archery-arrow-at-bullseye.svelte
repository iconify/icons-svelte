<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm2rlcwdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jm2rlcwdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:target-with-archery-arrow-at-bullseye" {...props}></Icon>
