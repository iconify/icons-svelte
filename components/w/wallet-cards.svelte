<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r_-i9nb0q.css';
import '../../css/f/fbpj6ebdl.css';
import '../../css/q/qjwo1qbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r_-i9nb0q"/><path class="fbpj6ebdl"/><path class="qjwo1qbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wallet-cards" {...props}></Icon>
