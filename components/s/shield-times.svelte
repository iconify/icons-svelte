<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma981cbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":2176};
const content = `<path class="ma981cbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:shield-times" {...props}></Icon>
