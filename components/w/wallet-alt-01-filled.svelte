<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewv7-z01s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewv7-z01s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-alt-01-filled" {...props}></Icon>
