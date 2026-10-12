<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rcofwzbcf.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/b/b9l-rx9lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rcofwzbcf"/><path class="s1a2eew1e"/><path class="b9l-rx9lv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wallet-cards-duotone" {...props}></Icon>
