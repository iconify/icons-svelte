<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljlzq2dvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljlzq2dvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:webcam-off" {...props}></Icon>
