<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ascow3bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ascow3bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-cursor" {...props}></Icon>
