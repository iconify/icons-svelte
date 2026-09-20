<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojjmu_19i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ojjmu_19i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:terminal-screen-with-dollar-prompt" {...props}></Icon>
