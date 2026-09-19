<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrj8e_b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zrj8e_b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:split" {...props}></Icon>
