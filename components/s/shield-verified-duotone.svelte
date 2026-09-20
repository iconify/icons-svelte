<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ge7mv6-bu.css';
import '../../css/j/jxib__s0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ge7mv6-bu"/><path class="jxib__s0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-verified-duotone" {...props}></Icon>
