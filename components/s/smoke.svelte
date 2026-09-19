<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/o/o59f9vbvm.css';
import '../../css/s/s4exkmb7g.css';
import '../../css/r/rnubj6bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="o59f9vbvm"/><path class="s4exkmb7g"/><path class="rnubj6bws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:smoke" {...props}></Icon>
