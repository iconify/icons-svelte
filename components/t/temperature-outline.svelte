<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ar-s6cb1i.css';
import '../../css/l/lruiq3bxa.css';
import '../../css/w/wdiux7bes.css';
import '../../css/r/r4byq35fv.css';
import '../../css/m/mlq6x5bsu.css';
import '../../css/l/l320lnnvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ar-s6cb1i"/><path class="lruiq3bxa"/><path clip-rule="evenodd" class="wdiux7bes"/><path clip-rule="evenodd" class="r4byq35fv"/><path class="mlq6x5bsu"/><path clip-rule="evenodd" class="l320lnnvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:temperature-outline" {...props}></Icon>
