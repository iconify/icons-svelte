<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4g_xmeih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4g_xmeih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-solid" {...props}></Icon>
