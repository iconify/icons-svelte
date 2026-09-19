<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d4hpaif8m.css';
import '../../css/i/isboikbqw.css';
import '../../css/m/m-bfnubcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d4hpaif8m"/><path class="isboikbqw"/><path class="m-bfnubcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:watch" {...props}></Icon>
