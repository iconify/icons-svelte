<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhvepq05d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rhvepq05d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:suit-club" {...props}></Icon>
