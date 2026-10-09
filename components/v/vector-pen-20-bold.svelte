<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izj2xgmec.css';
import '../../css/i/il1n2kszo.css';
import '../../css/j/jykge1big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="izj2xgmec"/><path class="il1n2kszo"/><path class="jykge1big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vector-pen-20-bold" {...props}></Icon>
