<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jrxssqnyz.css';
import '../../css/r/rzyzgqcqn.css';
import '../../css/t/ticjgqbdl.css';
import '../../css/f/fex6dubso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="jrxssqnyz"/><circle class="rzyzgqcqn"/><circle class="ticjgqbdl"/><path class="fex6dubso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:share" {...props}></Icon>
