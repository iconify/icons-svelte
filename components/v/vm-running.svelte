<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz8te_bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wz8te_bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:vm-running" {...props}></Icon>
