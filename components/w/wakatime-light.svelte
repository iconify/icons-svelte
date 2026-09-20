<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to5_hpm1w.css';
import '../../css/h/h3bp_99ap.css';
import '../../css/o/obovem3ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":340,"height":340};
const content = `<g class="to5_hpm1w"><path clip-rule="evenodd" class="h3bp_99ap"/><path class="obovem3ey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wakatime-light" {...props}></Icon>
