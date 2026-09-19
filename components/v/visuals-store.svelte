<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2-y50v-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r2-y50v-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:visuals-store" {...props}></Icon>
