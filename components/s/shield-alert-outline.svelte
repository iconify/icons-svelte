<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m5xe9ybcw.css';
import '../../css/c/cuogirb-s.css';
import '../../css/a/aln2yuqeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="shield-alert-outline"><g class="Vector cuyn6tgcc"><path clip-rule="evenodd" class="m5xe9ybcw"/><path clip-rule="evenodd" class="cuogirb-s"/><path class="aln2yuqeg"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:shield-alert-outline" {...props}></Icon>
