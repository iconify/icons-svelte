<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvw2c-b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wvw2c-b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wooden-fence" {...props}></Icon>
