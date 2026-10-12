<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fo5gddyxp.css';
import '../../css/n/nyv5_pnax.css';
import '../../css/i/il-hj08zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fo5gddyxp"/><path class="nyv5_pnax"/><path class="il-hj08zf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wallet-duotone" {...props}></Icon>
