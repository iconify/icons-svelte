<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9-8sac1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q9-8sac1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vscodium" {...props}></Icon>
