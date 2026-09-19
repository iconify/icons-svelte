<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7llo2a6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="l7llo2a6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ups" {...props}></Icon>
