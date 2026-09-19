<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-4k5kb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y-4k5kb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:wheelchair" {...props}></Icon>
