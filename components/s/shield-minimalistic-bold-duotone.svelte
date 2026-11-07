<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gry2dppuz.css';
import '../../css/l/lm1gwl2sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gry2dppuz"/><path class="lm1gwl2sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-bold-duotone" {...props}></Icon>
