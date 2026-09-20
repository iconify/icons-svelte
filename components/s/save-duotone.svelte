<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bn7_f-byy.css';
import '../../css/i/i3xud4bxc.css';
import '../../css/w/w98c_y1_f.css';
import '../../css/y/ygkk5s74q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="bn7_f-byy"/><path class="i3xud4bxc"/><path class="w98c_y1_f"/><path class="ygkk5s74q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:save-duotone" {...props}></Icon>
