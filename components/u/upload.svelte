<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch0locc9x.css';
import '../../css/v/vd3n2rbxy.css';
import '../../css/a/al_h_5jub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ch0locc9x"><path class="vd3n2rbxy"/><path class="al_h_5jub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:upload" {...props}></Icon>
