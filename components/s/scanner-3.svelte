<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd2q-gb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xd2q-gb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:scanner-3" {...props}></Icon>
