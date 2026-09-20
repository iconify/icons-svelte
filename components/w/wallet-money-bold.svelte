<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/umdn2-12o.css';
import '../../css/t/tlyq4trtp.css';
import '../../css/q/q8ae85b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="umdn2-12o"/><path clip-rule="evenodd" class="tlyq4trtp"/><path class="q8ae85b2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-money-bold" {...props}></Icon>
