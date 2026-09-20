<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz55z5bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uz55z5bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shopping-bag-hand-bag-2-remix" {...props}></Icon>
