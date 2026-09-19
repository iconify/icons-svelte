<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9noykrss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9noykrss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tired-eye" {...props}></Icon>
