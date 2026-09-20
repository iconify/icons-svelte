<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tx9t90agw.css';
import '../../css/c/cvmq7ekuv.css';
import '../../css/g/g7qnembxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tx9t90agw"/><path class="cvmq7ekuv"/><path class="g7qnembxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-off" {...props}></Icon>
