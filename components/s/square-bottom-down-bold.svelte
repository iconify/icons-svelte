<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdnocya5g.css';
import '../../css/s/sfzfjg58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdnocya5g"/><path class="sfzfjg58s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-bottom-down-bold" {...props}></Icon>
