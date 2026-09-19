<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh-9gdc_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qh-9gdc_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:surrounded-shield" {...props}></Icon>
