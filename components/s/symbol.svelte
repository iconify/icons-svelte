<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_4ensb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_4ensb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:symbol" {...props}></Icon>
