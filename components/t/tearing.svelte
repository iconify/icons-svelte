<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2culq2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ob2culq2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tearing" {...props}></Icon>
