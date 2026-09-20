<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1cn46ujl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1cn46ujl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-circle-filled" {...props}></Icon>
