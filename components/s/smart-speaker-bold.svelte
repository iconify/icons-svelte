<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oxm4exb-m.css';
import '../../css/o/o1kkk1b6e.css';
import '../../css/h/h8wwunb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oxm4exb-m"/><path class="o1kkk1b6e"/><path class="h8wwunb3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-speaker-bold" {...props}></Icon>
