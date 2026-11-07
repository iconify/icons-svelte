<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkyfhubwr.css';
import '../../css/z/zyz94_b1d.css';
import '../../css/k/ksibtyk_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkyfhubwr"/><path class="zyz94_b1d"/><path class="ksibtyk_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-pen-bold" {...props}></Icon>
