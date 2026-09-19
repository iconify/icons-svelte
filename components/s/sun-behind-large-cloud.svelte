<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jovek0baj.css';
import '../../css/m/mmdrd1b9q.css';
import '../../css/k/kvv6k2b5r.css';
import '../../css/s/s_faj7bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jovek0baj"/><path class="mmdrd1b9q"/><path class="kvv6k2b5r"/><path class="s_faj7bmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:sun-behind-large-cloud" {...props}></Icon>
