<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xha6szo1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xha6szo1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:suitcase-x" {...props}></Icon>
