<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3cbd4b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c3cbd4b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:weixin-cards-offers" {...props}></Icon>
