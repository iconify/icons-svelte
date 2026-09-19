<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex54bobeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ex54bobeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:send-mirrored" {...props}></Icon>
