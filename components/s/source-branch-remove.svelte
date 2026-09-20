<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1u69fbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u69fbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-branch-remove" {...props}></Icon>
