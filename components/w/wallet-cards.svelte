<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/npdjkvbfv.css';
import '../../css/p/pq80gbbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="npdjkvbfv"/><path class="pq80gbbxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wallet-cards" {...props}></Icon>
