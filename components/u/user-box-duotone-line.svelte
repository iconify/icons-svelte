<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y5--hccnw.css';
import '../../css/t/ts4_tacxb.css';
import '../../css/q/qy-x2bcjr.css';
import '../../css/y/ynhzcoben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y5--hccnw"/><path class="ts4_tacxb"/><circle class="qy-x2bcjr"/><rect class="ynhzcoben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-box-duotone-line" {...props}></Icon>
