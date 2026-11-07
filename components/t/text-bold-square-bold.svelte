<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krw35zlyq.css';
import '../../css/b/byoze1bep.css';
import '../../css/v/vdz_zbbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krw35zlyq"/><path class="byoze1bep"/><path clip-rule="evenodd" class="vdz_zbbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-square-bold" {...props}></Icon>
