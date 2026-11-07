<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg_fn_bfr.css';
import '../../css/z/z3e729uop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg_fn_bfr"/><path class="z3e729uop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:toolbox-bold-duotone" {...props}></Icon>
