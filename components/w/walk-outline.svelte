<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw1hwcn4c.css';
import '../../css/u/u7peyabnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zw1hwcn4c"/><circle class="u7peyabnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:walk-outline" {...props}></Icon>
