<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en2c70boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en2c70boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scanner-bold" {...props}></Icon>
