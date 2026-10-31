<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgbl2ybmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgbl2ybmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shirt-round" {...props}></Icon>
