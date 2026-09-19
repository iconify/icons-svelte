<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu6ajdafw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iu6ajdafw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:spinning-top" {...props}></Icon>
