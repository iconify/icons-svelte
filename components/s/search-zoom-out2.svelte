<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xojf1ebkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xojf1ebkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-out2" {...props}></Icon>
