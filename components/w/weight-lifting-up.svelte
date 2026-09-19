<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpx5clbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpx5clbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:weight-lifting-up" {...props}></Icon>
