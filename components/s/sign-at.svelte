<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gtt4t2bjv.css';
import '../../css/v/v999r7bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="gtt4t2bjv"/><path class="v999r7bpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sign-at" {...props}></Icon>
