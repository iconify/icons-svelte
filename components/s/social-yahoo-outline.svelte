<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egzdrq7kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="egzdrq7kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-yahoo-outline" {...props}></Icon>
