<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk9brtb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xk9brtb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-plus4-filled" {...props}></Icon>
