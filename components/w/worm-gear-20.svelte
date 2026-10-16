<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh5sn9n9c.css';
import '../../css/x/x9950ccly.css';
import '../../css/i/il2mnhbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qh5sn9n9c"/><path class="x9950ccly"/><path class="il2mnhbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:worm-gear-20" {...props}></Icon>
