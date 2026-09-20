<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkmi6bh9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nkmi6bh9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:subtitles" {...props}></Icon>
