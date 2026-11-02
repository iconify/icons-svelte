<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfnb6qb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfnb6qb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-right-open-line" {...props}></Icon>
