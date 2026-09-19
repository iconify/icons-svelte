<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt2gydb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qt2gydb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:shuffle" {...props}></Icon>
