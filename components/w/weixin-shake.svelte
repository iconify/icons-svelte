<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wau8bobcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wau8bobcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:weixin-shake" {...props}></Icon>
