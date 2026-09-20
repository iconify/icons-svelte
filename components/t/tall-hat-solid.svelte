<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd4vpr87g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dd4vpr87g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tall-hat-solid" {...props}></Icon>
