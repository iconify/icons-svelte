<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cewjf_06r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cewjf_06r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sharp-crown" {...props}></Icon>
