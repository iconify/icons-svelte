<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj8ilnbfl.css';
import '../../css/i/i7ws4lb4n.css';
import '../../css/c/cn0l77biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nj8ilnbfl"/><path class="i7ws4lb4n"/><path class="cn0l77biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:worm-gear-48" {...props}></Icon>
