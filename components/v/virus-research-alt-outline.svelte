<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fde1h0bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fde1h0bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-research-alt-outline" {...props}></Icon>
