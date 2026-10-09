<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewn1ke3br.css';
import '../../css/e/e3k76dbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="e3k76dbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sidebar-20" {...props}></Icon>
