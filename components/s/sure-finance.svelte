<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt6m2xbua.css';
import '../../css/u/u9cjpybxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pt6m2xbua"/><path class="u9cjpybxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sure-finance" {...props}></Icon>
