<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jlkh9zbwk.css';
import '../../css/o/oqa_tmuef.css';
import '../../css/c/c-oeh2kvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jlkh9zbwk"/><path class="oqa_tmuef"/><path clip-rule="evenodd" class="c-oeh2kvd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-alt-outline-24px" {...props}></Icon>
