<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1fv2s1fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1fv2s1fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-square-dot-vertical-filled" {...props}></Icon>
