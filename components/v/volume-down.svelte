<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxd94ib7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="xxd94ib7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:volume-down" {...props}></Icon>
