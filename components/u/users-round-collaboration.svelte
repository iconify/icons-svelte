<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v57c18mrt.css';
import '../../css/d/dto95jbvb.css';
import '../../css/v/vs6v5wbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v57c18mrt"/><circle class="dto95jbvb"/><circle class="vs6v5wbbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:users-round-collaboration" {...props}></Icon>
