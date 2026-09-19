<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otiz8qbou.css';
import '../../css/s/s2qmknl-c.css';
import '../../css/b/bz-nx6b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="otiz8qbou"/><path class="s2qmknl-c"/><path clip-rule="evenodd" class="bz-nx6b1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:taxi" {...props}></Icon>
