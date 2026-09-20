<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikim0yefd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikim0yefd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-fill" {...props}></Icon>
