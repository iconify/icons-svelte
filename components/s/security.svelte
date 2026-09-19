<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgfhitvgx.css';
import '../../css/w/wup9lynlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgfhitvgx"/><path class="wup9lynlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:security" {...props}></Icon>
