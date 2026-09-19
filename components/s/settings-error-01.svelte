<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m8am-9box.css';
import '../../css/h/hav_9b5ms.css';
import '../../css/m/mrlb7pzin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m8am-9box"/><path class="hav_9b5ms"/><path class="mrlb7pzin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:settings-error-01" {...props}></Icon>
