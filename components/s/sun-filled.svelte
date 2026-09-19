<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bch5yjxyw.css';
import '../../css/j/j6p__-b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bch5yjxyw"/><path clip-rule="evenodd" class="j6p__-b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:sun-filled" {...props}></Icon>
