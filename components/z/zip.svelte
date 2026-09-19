<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/x/x26h1bcsq.css';
import '../../css/k/krktdhbhc.css';
import '../../css/p/p49jg_bkb.css';
import '../../css/k/kbzffqb0y.css';
import '../../css/t/tyj92tbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="x26h1bcsq"/><path class="krktdhbhc"/><path clip-rule="evenodd" class="p49jg_bkb"/><path class="kbzffqb0y"/><path class="tyj92tbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:zip" {...props}></Icon>
