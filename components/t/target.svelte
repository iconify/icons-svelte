<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/axarcbb2r.css';
import '../../css/r/rikk_tbdt.css';
import '../../css/n/n1xy6nh9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="axarcbb2r"/><circle class="rikk_tbdt"/><circle class="n1xy6nh9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:target" {...props}></Icon>
