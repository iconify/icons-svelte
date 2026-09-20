<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv0sy5bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv0sy5bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:view-list" {...props}></Icon>
