<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq0wx8bxg.css';
import '../../css/s/sczabacxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq0wx8bxg"/><path class="sczabacxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:wallet" {...props}></Icon>
