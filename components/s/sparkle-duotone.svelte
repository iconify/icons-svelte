<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzh2_5mwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzh2_5mwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sparkle-duotone" {...props}></Icon>
