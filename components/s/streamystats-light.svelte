<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl35mubuy.css';
import '../../css/w/wfpw4achp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cl35mubuy"/><path class="wfpw4achp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamystats-light" {...props}></Icon>
