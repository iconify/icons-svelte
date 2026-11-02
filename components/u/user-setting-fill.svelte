<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_e3_7ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_e3_7ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-setting-fill" {...props}></Icon>
