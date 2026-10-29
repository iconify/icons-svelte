<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/z8qchacao.css';
import '../../css/e/egr27nbzr.css';
import '../../css/x/x1_r36phd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco z8qchacao"/><path class="egr27nbzr wm-k"/><path class="wm-a x1_r36phd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:test-tube-blueprint" {...props}></Icon>
