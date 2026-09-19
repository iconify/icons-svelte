<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y8pk6r70x.css';
import '../../css/p/pq-3x51-i.css';
import '../../css/g/gs98bbbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y8pk6r70x"/><path class="pq-3x51-i"/><path class="gs98bbbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:shopping-mall" {...props}></Icon>
