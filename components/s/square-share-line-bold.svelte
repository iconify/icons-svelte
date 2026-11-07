<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldr9qjosp.css';
import '../../css/p/pdyp1acvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldr9qjosp"/><path clip-rule="evenodd" class="pdyp1acvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-share-line-bold" {...props}></Icon>
