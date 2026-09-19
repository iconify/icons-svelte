<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w--_r6b_t.css';
import '../../css/g/gq0l-nfit.css';
import '../../css/h/hmy4ymk6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="w--_r6b_t"/><path class="gq0l-nfit"/><path clip-rule="evenodd" class="hmy4ymk6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:wifi" {...props}></Icon>
