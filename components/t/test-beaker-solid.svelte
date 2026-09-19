<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dktzsj1sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dktzsj1sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:test-beaker-solid" {...props}></Icon>
