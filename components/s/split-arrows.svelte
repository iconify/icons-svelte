<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-hns2b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-hns2b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:split-arrows" {...props}></Icon>
