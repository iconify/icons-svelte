<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5yhmcb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="w5yhmcb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield" {...props}></Icon>
