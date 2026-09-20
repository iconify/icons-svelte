<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bo7bp7bqb.css';
import '../../css/g/gzlm1jb-p.css';
import '../../css/q/qe99iznek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bo7bp7bqb"/><path class="gzlm1jb-p"/><path class="qe99iznek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stethoscope" {...props}></Icon>
