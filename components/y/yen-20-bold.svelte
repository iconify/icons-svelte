<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h92390rbo.css';
import '../../css/a/a7fz73bbw.css';
import '../../css/f/f3vfs2z_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h92390rbo"/><path class="a7fz73bbw"/><path class="f3vfs2z_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yen-20-bold" {...props}></Icon>
