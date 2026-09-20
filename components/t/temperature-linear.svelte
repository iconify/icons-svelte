<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/ror8fyj6a.css';
import '../../css/u/ul0rk9bgh.css';
import '../../css/w/w29ath28m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ror8fyj6a"/><path class="ul0rk9bgh"/><path class="w29ath28m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:temperature-linear" {...props}></Icon>
