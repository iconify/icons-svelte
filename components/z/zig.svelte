<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy_v_8_dd.css';
import '../../css/a/a38e_428a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wy_v_8_dd"/><path class="a38e_428a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:zig" {...props}></Icon>
