<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ay-6ct32d.css';
import '../../css/s/susx8mqow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ay-6ct32d"/><path class="susx8mqow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:tag" {...props}></Icon>
