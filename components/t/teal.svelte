<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5_mjzf7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5_mjzf7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:teal" {...props}></Icon>
