<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzb7-dbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzb7-dbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-plus-solid" {...props}></Icon>
