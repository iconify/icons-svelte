<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku9t6xbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku9t6xbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:switzerland" {...props}></Icon>
