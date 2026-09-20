<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0p3p0bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0p3p0bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-minus-2" {...props}></Icon>
