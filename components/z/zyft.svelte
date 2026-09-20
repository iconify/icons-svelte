<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-fsm3b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":160,"height":62};
const content = `<path class="m-fsm3b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zyft" {...props}></Icon>
