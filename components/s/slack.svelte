<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emuy9lbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="emuy9lbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:slack" {...props}></Icon>
