<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbhcn1b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbhcn1b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:store-2-line" {...props}></Icon>
