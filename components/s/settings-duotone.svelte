<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wdk_g3xvk.css';
import '../../css/o/ok_35jzyh.css';
import '../../css/q/qv0rtbbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wdk_g3xvk"/><circle class="ok_35jzyh"/><path class="qv0rtbbbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:settings-duotone" {...props}></Icon>
