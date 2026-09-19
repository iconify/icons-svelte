<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/o/oa0-72i1l.css';
import '../../css/q/qu5nk8u-q.css';
import '../../css/p/p9ojn-bgd.css';
import '../../css/o/oa9d-wg2b.css';
import '../../css/u/uar13_bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="oa0-72i1l"/><path class="qu5nk8u-q"/><path class="p9ojn-bgd"/><path class="oa9d-wg2b"/><path class="uar13_bfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:uz" {...props}></Icon>
