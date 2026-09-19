<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cny4agblb.css';
import '../../css/a/ad1pplybg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cny4agblb"/><path class="ad1pplybg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sun-one" {...props}></Icon>
