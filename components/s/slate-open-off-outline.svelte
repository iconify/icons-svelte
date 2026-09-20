<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xshlwsaiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xshlwsaiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slate-open-off-outline" {...props}></Icon>
