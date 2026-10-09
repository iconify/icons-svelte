<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx2n-7xqn.css';
import '../../css/b/bpbl5vkki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zx2n-7xqn"/><path class="bpbl5vkki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:router-20" {...props}></Icon>
