<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w334vybwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w334vybwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:table" {...props}></Icon>
