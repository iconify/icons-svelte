<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtu-8o8di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtu-8o8di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:suckless" {...props}></Icon>
