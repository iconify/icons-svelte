<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao01rhb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ao01rhb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:weixin-scan" {...props}></Icon>
