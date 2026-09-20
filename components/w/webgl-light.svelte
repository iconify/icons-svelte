<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q30p7tbwg.css';
import '../../css/b/b4628owed.css';
import '../../css/f/fzgukmboj.css';
import '../../css/g/gahp4sboa.css';
import '../../css/t/tx072rjnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":500};
const content = `<path class="q30p7tbwg"/><g class="b4628owed"><path class="fzgukmboj"/><path class="gahp4sboa"/></g><path class="tx072rjnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webgl-light" {...props}></Icon>
