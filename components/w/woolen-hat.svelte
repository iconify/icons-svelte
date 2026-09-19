<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mw0vcbb6f.css';
import '../../css/r/r55hgqb1c.css';
import '../../css/r/r8r7mgbbj.css';
import '../../css/p/peqvy84ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="mw0vcbb6f"/><path class="r55hgqb1c"/><circle class="r8r7mgbbj"/><path class="peqvy84ye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:woolen-hat" {...props}></Icon>
