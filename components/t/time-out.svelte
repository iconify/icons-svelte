<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh2ol5bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mh2ol5bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:time-out" {...props}></Icon>
