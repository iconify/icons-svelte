<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';
import '../../css/o/o1xn36blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu18-_bab"/><path class="lg9shfpyb"/><path clip-rule="evenodd" class="o1xn36blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-circle-2-outline" {...props}></Icon>
