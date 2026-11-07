<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3n43-bnv.css';
import '../../css/t/tjg1izbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n43-bnv"/><path clip-rule="evenodd" class="tjg1izbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-minimalistic-bold" {...props}></Icon>
