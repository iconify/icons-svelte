<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djdzd-6ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djdzd-6ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:t-shirt-fill" {...props}></Icon>
