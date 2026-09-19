<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ki4vmlb-h.css';
import '../../css/f/fqwam5hgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="cuyn6tgcc"><path class="ki4vmlb-h"/><path class="fqwam5hgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-tux" {...props}></Icon>
