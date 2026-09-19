<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g270unitk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g270unitk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spears" {...props}></Icon>
