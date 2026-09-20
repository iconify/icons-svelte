<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a012c5bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a012c5bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:send" {...props}></Icon>
