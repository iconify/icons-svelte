<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/ger8efbfa.css';
import '../../css/q/qd88d0khh.css';
import '../../css/v/vrs_4bc9h.css';
import '../../css/s/s56xsmbuu.css';
import '../../css/g/g5v-35ucj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ger8efbfa"/><path class="qd88d0khh"/><path class="vrs_4bc9h"/><path class="s56xsmbuu"/><path class="g5v-35ucj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-money-line-duotone" {...props}></Icon>
