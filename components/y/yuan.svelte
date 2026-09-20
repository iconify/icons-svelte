<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsj9wgbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lsj9wgbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:yuan" {...props}></Icon>
