<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahp9sifuv.css';
import '../../css/f/f8g2gccrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahp9sifuv"/><path class="f8g2gccrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-setting-filled" {...props}></Icon>
