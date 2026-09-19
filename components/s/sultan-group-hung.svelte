<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpvilr8cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpvilr8cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sultan-group-hung" {...props}></Icon>
