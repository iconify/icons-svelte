<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik16rebhe.css';
import '../../css/e/ekcn2ur9m.css';
import '../../css/i/i_cqwtblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ik16rebhe"/><path class="ekcn2ur9m"/><path class="i_cqwtblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:streamlit" {...props}></Icon>
