<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1dt1gbdl.css';
import '../../css/r/r6mz58bje.css';
import '../../css/z/z08a_ruyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t1dt1gbdl"/><path class="r6mz58bje"/><path class="z08a_ruyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tv-outline" {...props}></Icon>
