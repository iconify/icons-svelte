<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-mr4fbpj.css';
import '../../css/o/os71ptboc.css';
import '../../css/x/xiq0mebla.css';
import '../../css/b/byz412mey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":192};
const content = `<path class="l-mr4fbpj"/><circle class="os71ptboc"/><path class="xiq0mebla"/><path class="byz412mey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:youtube-music" {...props}></Icon>
