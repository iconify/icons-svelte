<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3cuan7wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3cuan7wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trilobite" {...props}></Icon>
