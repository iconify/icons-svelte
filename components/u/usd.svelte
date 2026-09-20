<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdkp318ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdkp318ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:usd" {...props}></Icon>
