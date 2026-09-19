<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t89f95b8p.css';
import '../../css/b/bsnrj6lbv.css';
import '../../css/i/ivdx5lb0c.css';
import '../../css/l/lc2yt8urn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t89f95b8p"/><path class="bsnrj6lbv"/><path class="ivdx5lb0c"/><path class="lc2yt8urn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user-circle-outline" {...props}></Icon>
