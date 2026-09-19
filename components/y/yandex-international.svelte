<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec4bcwb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ec4bcwb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:yandex-international" {...props}></Icon>
