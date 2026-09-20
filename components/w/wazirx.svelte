<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i75_g2pth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i75_g2pth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wazirx" {...props}></Icon>
