<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy178tbuh.css';
import '../../css/s/skftdzbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy178tbuh"/><path class="skftdzbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-minimalistic-horizontal-bold-duotone" {...props}></Icon>
