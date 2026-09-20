<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fwts3rb1g.css';
import '../../css/v/vx2u40beg.css';
import '../../css/n/ndchddcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="fwts3rb1g"/><path clip-rule="evenodd" class="vx2u40beg"/><path class="ndchddcke"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-add-duotone-line" {...props}></Icon>
