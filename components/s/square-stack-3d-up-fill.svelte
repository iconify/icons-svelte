<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkaf7bbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qkaf7bbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-stack-3d-up-fill" {...props}></Icon>
