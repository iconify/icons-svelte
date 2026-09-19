<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_iv796sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_iv796sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:telegram" {...props}></Icon>
