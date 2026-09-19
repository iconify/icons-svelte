<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jee5y5ssn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jee5y5ssn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skirt" {...props}></Icon>
