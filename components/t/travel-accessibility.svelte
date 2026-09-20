<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr32yxbru.css';
import '../../css/a/aa4zmqbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hr32yxbru"/><path clip-rule="evenodd" class="aa4zmqbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:travel-accessibility" {...props}></Icon>
