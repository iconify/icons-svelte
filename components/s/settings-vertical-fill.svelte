<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf5r8qbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf5r8qbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-vertical-fill" {...props}></Icon>
