<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1bfxqbht.css';
import '../../css/q/q_szi_b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bfxqbht"/><path class="q_szi_b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-left-bold-duotone" {...props}></Icon>
