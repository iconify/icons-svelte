<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd-bllh8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fd-bllh8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-arrow-up" {...props}></Icon>
