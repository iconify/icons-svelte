<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce06y8b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ce06y8b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:tgch" {...props}></Icon>
