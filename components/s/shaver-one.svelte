<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/h2kar04zl.css';
import '../../css/g/gwrmm3xbs.css';
import '../../css/f/ft6udiq_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="h2kar04zl"/><path class="gwrmm3xbs"/><circle class="ft6udiq_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shaver-one" {...props}></Icon>
