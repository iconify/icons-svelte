<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7gxj6bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s7gxj6bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-above-water" {...props}></Icon>
