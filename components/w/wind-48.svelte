<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk1y4abcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zk1y4abcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-48" {...props}></Icon>
