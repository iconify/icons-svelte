<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxaoy2jxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bxaoy2jxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:windmill-two" {...props}></Icon>
