<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-wmiybgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-wmiybgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tree-03" {...props}></Icon>
