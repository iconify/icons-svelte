<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7lpn1bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7lpn1bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-right-line" {...props}></Icon>
