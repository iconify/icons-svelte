<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p95pe0_jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p95pe0_jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-twitter" {...props}></Icon>
