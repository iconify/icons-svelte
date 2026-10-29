<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/khn241bad.css';
import '../../css/n/npa4rgbjd.css';
import '../../css/l/ljcz9bcpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="khn241bad"/><path class="npa4rgbjd"/><path class="ljcz9bcpj wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-pen-solid" {...props}></Icon>
