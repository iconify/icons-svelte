<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/c974-jgxw.css';
import '../../css/h/hi4pc4bnr.css';
import '../../css/v/v15isc0yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="c974-jgxw"/><circle class="hi4pc4bnr"/><circle class="v15isc0yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:skull" {...props}></Icon>
