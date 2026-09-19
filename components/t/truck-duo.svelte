<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pm0g03ory.css';
import '../../css/c/c3yk-nbbq.css';
import '../../css/o/ozqsb-b4p.css';
import '../../css/j/jcgz6bcws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pm0g03ory"/><path class="c3yk-nbbq"/><path class="ozqsb-b4p"/><path class="jcgz6bcws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:truck-duo" {...props}></Icon>
