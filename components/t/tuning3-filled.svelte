<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akj5c-bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akj5c-bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tuning3-filled" {...props}></Icon>
