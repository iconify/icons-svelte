<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_aqub-c.css';
import '../../css/t/tcimq1bdm.css';
import '../../css/x/x3wytyg0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<defs><clipPath id="SVGrR3hXb3H"><path class="f7_aqub-c"/></clipPath></defs><g clip-path="url(#SVGrR3hXb3H)"><path class="tcimq1bdm"/></g><path class="x3wytyg0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sema-wordmark" {...props}></Icon>
