<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aov95pblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aov95pblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shop3-filled" {...props}></Icon>
