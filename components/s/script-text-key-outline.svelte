<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njb223hhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njb223hhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:script-text-key-outline" {...props}></Icon>
