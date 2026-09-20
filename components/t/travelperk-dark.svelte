<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qonlf4bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qonlf4bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:travelperk-dark" {...props}></Icon>
