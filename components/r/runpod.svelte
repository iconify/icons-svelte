<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uij4f5b-x.css';
import '../../css/g/gx4suybiw.css';
import '../../css/i/i2ivzmcfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":141,"height":32};
const content = `<g class="uij4f5b-x"><path clip-rule="evenodd" class="gx4suybiw"/><path class="i2ivzmcfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:runpod" {...props}></Icon>
