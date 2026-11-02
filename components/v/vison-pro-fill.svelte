<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfnd5x6bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfnd5x6bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vison-pro-fill" {...props}></Icon>
