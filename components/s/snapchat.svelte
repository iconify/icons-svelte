<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lubrr7x8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lubrr7x8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:snapchat" {...props}></Icon>
