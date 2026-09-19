<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsfkz5ysl.css';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e7pn7ylvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<mask id="SVGmUZuRdkM" width="48" height="48" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="fsfkz5ysl"/></mask><g mask="url(#SVGmUZuRdkM)" class="nz_20wbpz"><path class="e7pn7ylvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:upload" {...props}></Icon>
