<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_825rb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_825rb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:streets-filled" {...props}></Icon>
