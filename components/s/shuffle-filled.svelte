<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlciivbhx.css';
import '../../css/q/qhg6yeb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlciivbhx"/><path class="qhg6yeb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shuffle-filled" {...props}></Icon>
