<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fey1rubmg.css';
import '../../css/k/kgcxlh52x.css';
import '../../css/m/mo3nibcdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fey1rubmg"/><path class="kgcxlh52x"/><path class="mo3nibcdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-game-360-vr" {...props}></Icon>
