<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh1ztlbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vh1ztlbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:trend-up-solid" {...props}></Icon>
