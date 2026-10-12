<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eff4cabla.css';
import '../../css/g/gg3es5x5l.css';
import '../../css/i/i5b16xb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eff4cabla"/><path class="gg3es5x5l"/><path class="i5b16xb_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trash-duotone" {...props}></Icon>
