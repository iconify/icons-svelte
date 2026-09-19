<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtr-b-c8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtr-b-c8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sleeveless-jacket" {...props}></Icon>
