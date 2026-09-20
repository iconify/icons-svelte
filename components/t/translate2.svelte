<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/parj1ac3o.css';
import '../../css/d/d0i3ffawj.css';
import '../../css/l/l10rdjyqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="parj1ac3o"/><path class="d0i3ffawj"/><path clip-rule="evenodd" class="l10rdjyqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:translate2" {...props}></Icon>
