<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_je-3caz.css';
import '../../css/j/jmyvgu6pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x_je-3caz"/><path class="jmyvgu6pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:streamlit" {...props}></Icon>
