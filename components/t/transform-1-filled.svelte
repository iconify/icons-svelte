<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-8nb7x6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-8nb7x6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:transform-1-filled" {...props}></Icon>
