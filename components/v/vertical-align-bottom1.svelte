<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2_1icpng.css';
import '../../css/x/xi4z0dojk.css';
import '../../css/h/hltazq3ru.css';
import '../../css/o/o_a2bsbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_1icpng"/><path class="xi4z0dojk"/><path class="hltazq3ru"/><path class="o_a2bsbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:vertical-align-bottom1" {...props}></Icon>
