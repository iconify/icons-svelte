<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/byhi3osvb.css';
import '../../css/g/gbfhxvenz.css';
import '../../css/w/wa-ouos2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="byhi3osvb"/><path class="gbfhxvenz"/><path class="wa-ouos2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:terminal-rectangle" {...props}></Icon>
