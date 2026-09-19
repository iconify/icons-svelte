<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwltb-50z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pwltb-50z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:view-3d" {...props}></Icon>
