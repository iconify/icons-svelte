<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq6vkhbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq6vkhbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shrink" {...props}></Icon>
