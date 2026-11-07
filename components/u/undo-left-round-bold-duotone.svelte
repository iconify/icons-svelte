<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_m1grh8p.css';
import '../../css/j/jdaorxbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_m1grh8p"/><path class="jdaorxbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-round-bold-duotone" {...props}></Icon>
