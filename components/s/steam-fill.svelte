<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wflzmz97l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wflzmz97l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:steam-fill" {...props}></Icon>
