<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3t-g3ebi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y3t-g3ebi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:screen-curve-solid" {...props}></Icon>
