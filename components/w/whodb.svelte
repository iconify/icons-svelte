<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br-__gb2m.css';
import '../../css/a/a_399pbtf.css';
import '../../css/s/scjdmkghe.css';
import '../../css/h/h73mrwbie.css';
import '../../css/p/pgzmr_bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="br-__gb2m"/><path class="a_399pbtf"/><path class="scjdmkghe"/><path class="h73mrwbie"/><path class="pgzmr_bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whodb" {...props}></Icon>
