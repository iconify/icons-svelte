<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/it5js_8rn.css';
import '../../css/g/gp0egaclj.css';
import '../../css/h/hwlwzjglt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="it5js_8rn"/><circle class="gp0egaclj"/><path class="hwlwzjglt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:switch-camera" {...props}></Icon>
