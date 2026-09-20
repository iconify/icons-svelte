<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foe4c7nyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="foe4c7nyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tree-two-level" {...props}></Icon>
