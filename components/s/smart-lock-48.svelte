<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg3h39b1g.css';
import '../../css/a/ah-ntwbee.css';
import '../../css/z/zi1nuachi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eg3h39b1g"/><path class="ah-ntwbee"/><path class="zi1nuachi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-lock-48" {...props}></Icon>
