<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgf6p-wjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgf6p-wjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:window-section" {...props}></Icon>
