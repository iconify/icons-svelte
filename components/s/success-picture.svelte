<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z_9nbbmkw.css';
import '../../css/n/ncl-bp61j.css';
import '../../css/k/k4liqx2ro.css';
import '../../css/o/o7ck84b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="z_9nbbmkw"/><path class="ncl-bp61j"/><path class="k4liqx2ro"/><path class="o7ck84b0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:success-picture" {...props}></Icon>
