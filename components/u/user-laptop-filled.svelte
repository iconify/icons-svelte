<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zfqeopbvu.css';
import '../../css/i/imc9g1buu.css';
import '../../css/z/z0dqlcz2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zfqeopbvu"/><path clip-rule="evenodd" class="imc9g1buu"/><path class="z0dqlcz2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-laptop-filled" {...props}></Icon>
