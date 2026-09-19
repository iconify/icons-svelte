<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/w/w80ub_bgs.css';
import '../../css/g/gz22pbbvy.css';
import '../../css/i/i-r6eqbky.css';
import '../../css/c/ca0jvcbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="w80ub_bgs"/><path class="gz22pbbvy"/><path class="i-r6eqbky"/><path class="ca0jvcbbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:save-one" {...props}></Icon>
