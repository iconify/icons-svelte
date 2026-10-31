<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuu6lyu_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuu6lyu_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:venus-fill-round" {...props}></Icon>
