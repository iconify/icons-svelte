<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfr0mcqvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vfr0mcqvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:warning" {...props}></Icon>
