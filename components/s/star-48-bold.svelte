<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqjxfbcli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bqjxfbcli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-48-bold" {...props}></Icon>
