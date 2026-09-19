<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pscnzhg3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1664};
const content = `<path class="pscnzhg3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sex-female" {...props}></Icon>
