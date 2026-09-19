<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsr5subpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fsr5subpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:work-item-bar" {...props}></Icon>
