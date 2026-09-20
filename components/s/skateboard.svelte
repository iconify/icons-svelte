<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd45dbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rfd45dbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:skateboard" {...props}></Icon>
