<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff3rfh2ld.css';
import '../../css/l/les5albff.css';
import '../../css/t/toxedhbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3rfh2ld"/><path class="les5albff"/><path class="toxedhbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zcx" {...props}></Icon>
