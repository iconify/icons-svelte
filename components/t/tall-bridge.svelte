<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl__lrbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl__lrbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tall-bridge" {...props}></Icon>
