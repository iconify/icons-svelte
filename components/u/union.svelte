<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e66ctgbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e66ctgbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:union" {...props}></Icon>
