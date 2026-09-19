<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf-9gnbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xf-9gnbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:transgender-outline" {...props}></Icon>
