<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nk-ja5bdx.css';
import '../../css/d/dfvj5ji8e.css';
import '../../css/b/bf57v-qce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nk-ja5bdx"/><path class="dfvj5ji8e"/><path class="bf57v-qce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:spaces" {...props}></Icon>
