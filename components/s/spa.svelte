<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2wc4bb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2wc4bb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:spa" {...props}></Icon>
