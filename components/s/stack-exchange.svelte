<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_q-1whlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_q-1whlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stack-exchange" {...props}></Icon>
