<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/avz07eylb.css';
import '../../css/b/b0bb4sbnm.css';
import '../../css/p/plmlc6b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="avz07eylb"/><path class="b0bb4sbnm"/><path class="plmlc6b1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tennis-bold" {...props}></Icon>
