<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7vsc55kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7vsc55kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:weixin-favorites" {...props}></Icon>
