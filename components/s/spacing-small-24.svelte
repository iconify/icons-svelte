<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk54-pk0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk54-pk0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:spacing-small-24" {...props}></Icon>
