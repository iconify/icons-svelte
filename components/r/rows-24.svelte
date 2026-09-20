<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgw-q5she.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgw-q5she"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rows-24" {...props}></Icon>
