<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7_g8vbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n7_g8vbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sorcerer-hat" {...props}></Icon>
