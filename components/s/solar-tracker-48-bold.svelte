<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqs_8pbmm.css';
import '../../css/k/k67ptjbwx.css';
import '../../css/n/nvywobb1g.css';
import '../../css/p/pse5d0bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qqs_8pbmm"/><path class="k67ptjbwx"/><path class="nvywobb1g"/><path class="pse5d0bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-tracker-48-bold" {...props}></Icon>
