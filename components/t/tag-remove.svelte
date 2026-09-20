<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fz5zvs8hu.css';
import '../../css/q/qqd875bhp.css';
import '../../css/o/orj139bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fz5zvs8hu"/><circle transform="rotate(-45 8.658 6.738)" class="qqd875bhp"/><path class="orj139bgi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:tag-remove" {...props}></Icon>
