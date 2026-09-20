<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnn_le0bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn_le0bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-grin-24" {...props}></Icon>
