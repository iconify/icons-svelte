<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxnxazn8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxnxazn8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:van-damme-split" {...props}></Icon>
