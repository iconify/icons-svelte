<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hep1bmbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hep1bmbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:window-browser-small" {...props}></Icon>
