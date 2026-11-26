<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbpnb1b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbpnb1b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rows-2-plus-bottom" {...props}></Icon>
