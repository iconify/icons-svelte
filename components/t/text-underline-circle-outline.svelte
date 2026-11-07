<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9tzwj7ok.css';
import '../../css/b/bzy5eobti.css';
import '../../css/f/fhxzx1b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9tzwj7ok"/><path class="bzy5eobti"/><path clip-rule="evenodd" class="fhxzx1b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-circle-outline" {...props}></Icon>
