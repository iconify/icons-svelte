<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v6ulq6e-s.css';
import '../../css/y/yr1mq_boa.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v6ulq6e-s"/><path clip-rule="evenodd" class="yr1mq_boa"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:triangle-down-filled-off" {...props}></Icon>
