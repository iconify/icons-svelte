<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb1vc-e3r.css';
import '../../css/x/xs322_bdu.css';
import '../../css/b/bm-jhkqqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="tb1vc-e3r"/><path class="xs322_bdu"/><path class="bm-jhkqqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:soccer" {...props}></Icon>
