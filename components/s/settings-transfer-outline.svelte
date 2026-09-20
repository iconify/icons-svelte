<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcft1hvhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcft1hvhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-transfer-outline" {...props}></Icon>
