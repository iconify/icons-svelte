<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f361_3bvh.css';
import '../../css/d/dsdw_xbyj.css';
import '../../css/i/iclwnvkbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f361_3bvh"/><path class="dsdw_xbyj"/><path class="iclwnvkbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sprout-duotone" {...props}></Icon>
