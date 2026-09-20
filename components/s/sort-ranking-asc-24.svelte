<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl4fp4vpe.css';
import '../../css/p/p_sp1no_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl4fp4vpe"/><path clip-rule="evenodd" class="p_sp1no_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-ranking-asc-24" {...props}></Icon>
