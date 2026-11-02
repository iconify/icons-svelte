<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xye12b3il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xye12b3il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:table-line" {...props}></Icon>
