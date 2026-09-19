<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqo2eehvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqo2eehvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sniffing-dog" {...props}></Icon>
