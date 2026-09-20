<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7d5s2ykc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7d5s2ykc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-branch-refresh" {...props}></Icon>
