<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rwzi9g3uh.css';
import '../../css/n/nhrqm3bvg.css';
import '../../css/p/pgd03r94f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwzi9g3uh"/><path class="nhrqm3bvg"/><path class="pgd03r94f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-square-rounded" {...props}></Icon>
