<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws0_qmb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ws0_qmb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sliders2" {...props}></Icon>
