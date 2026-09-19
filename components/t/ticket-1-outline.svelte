<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jqs04xbzn.css';
import '../../css/s/s2m1y1bld.css';
import '../../css/w/w3thj6b5k.css';
import '../../css/q/qvosn3u-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jqs04xbzn"/><path class="s2m1y1bld"/><path class="w3thj6b5k"/><path class="qvosn3u-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ticket-1-outline" {...props}></Icon>
