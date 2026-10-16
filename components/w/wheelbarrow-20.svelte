<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_53abzu.css';
import '../../css/i/ijjhc3b5x.css';
import '../../css/u/uv47p4bdr.css';
import '../../css/f/f3itb8bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lh_53abzu"/><path class="ijjhc3b5x"/><path class="uv47p4bdr"/><path class="f3itb8bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wheelbarrow-20" {...props}></Icon>
