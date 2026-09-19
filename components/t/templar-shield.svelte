<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkxyh8svy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rkxyh8svy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:templar-shield" {...props}></Icon>
