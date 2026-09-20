<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6vvpccox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6vvpccox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:smile-filled" {...props}></Icon>
