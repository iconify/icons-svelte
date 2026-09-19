<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/omv99sb0f.css';
import '../../css/q/qxcdtgl1w.css';
import '../../css/w/wttawfb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="omv99sb0f"/><path class="qxcdtgl1w"/><path class="wttawfb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tablet-connected-bluetooth" {...props}></Icon>
