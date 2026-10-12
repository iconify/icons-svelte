<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhpma-sca.css';
import '../../css/k/kyb_5vwwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vhpma-sca"/><path class="kyb_5vwwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:trash-stroke-20" {...props}></Icon>
