<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn2reo3hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pn2reo3hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:save" {...props}></Icon>
