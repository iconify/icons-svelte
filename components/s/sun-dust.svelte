<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvm7s_btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dvm7s_btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-dust" {...props}></Icon>
