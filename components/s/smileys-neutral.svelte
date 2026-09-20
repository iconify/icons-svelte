<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg0vg_p2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yg0vg_p2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:smileys-neutral" {...props}></Icon>
