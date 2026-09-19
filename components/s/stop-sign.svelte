<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg_f1--9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg_f1--9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:stop-sign" {...props}></Icon>
