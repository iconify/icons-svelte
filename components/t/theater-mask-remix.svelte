<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdo5itbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hdo5itbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:theater-mask-remix" {...props}></Icon>
