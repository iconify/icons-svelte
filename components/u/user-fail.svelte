<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1wgygbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j1wgygbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-fail" {...props}></Icon>
