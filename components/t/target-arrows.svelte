<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qns9xzolk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qns9xzolk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:target-arrows" {...props}></Icon>
