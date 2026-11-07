<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1bfxqbht.css';
import '../../css/e/e7qclfbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1bfxqbht"/><path class="e7qclfbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-left-bold-duotone" {...props}></Icon>
