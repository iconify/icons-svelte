<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9w_hblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":572,"height":717};
const content = `<path class="eo9w_hblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:trash" {...props}></Icon>
