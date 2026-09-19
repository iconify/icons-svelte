<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg9fendhi.css';
import '../../css/p/pzsltxbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mg9fendhi"/><path class="pzsltxbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wallet" {...props}></Icon>
