<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj83x2bwg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/ggubv6whl.css';
import '../../css/v/vt6-fiosq.css';
import '../../css/p/p46zpu12j.css';
import '../../css/k/k06lkun7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj83x2bwg secondary"/><g class="dt0cm9dhy primary"><path class="ggubv6whl"/><path class="vt6-fiosq"/><path class="p46zpu12j"/><path class="k06lkun7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spotify-duo" {...props}></Icon>
