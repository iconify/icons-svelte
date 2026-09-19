<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmdp-p_5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rmdp-p_5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-up-on-square-fill" {...props}></Icon>
