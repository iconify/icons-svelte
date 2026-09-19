<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl_5jt7fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kl_5jt7fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sandstorm" {...props}></Icon>
