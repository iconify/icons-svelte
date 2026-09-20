<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqxuq9btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqxuq9btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-cellular-off-line" {...props}></Icon>
