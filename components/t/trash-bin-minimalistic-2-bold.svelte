<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3n43-bnv.css';
import '../../css/l/lax56ybee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n43-bnv"/><path class="lax56ybee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-minimalistic-2-bold" {...props}></Icon>
