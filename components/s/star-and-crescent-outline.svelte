<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ih--ifrdt.css';
import '../../css/c/cqyqpbkvg.css';
import '../../css/d/d5vtl26pr.css';
import '../../css/b/bt0dx5bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ih--ifrdt"/><path class="cqyqpbkvg"/><path class="d5vtl26pr"/><path class="bt0dx5bel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-and-crescent-outline" {...props}></Icon>
