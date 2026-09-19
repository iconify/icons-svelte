<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzt7ai2sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dzt7ai2sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:xylophone" {...props}></Icon>
