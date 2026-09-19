<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqbwznbuj.css';
import '../../css/w/wg_xn1bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zqbwznbuj"/><path class="wg_xn1bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:split" {...props}></Icon>
