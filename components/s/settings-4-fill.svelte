<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcze9xoaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcze9xoaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-4-fill" {...props}></Icon>
