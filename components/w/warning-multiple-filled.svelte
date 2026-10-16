<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dff48eqvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dff48eqvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-multiple-filled" {...props}></Icon>
