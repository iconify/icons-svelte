<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqr8a7b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqr8a7b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stone-sphere" {...props}></Icon>
