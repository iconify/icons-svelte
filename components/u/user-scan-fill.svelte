<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/urz-4cihd.css';
import '../../css/z/z77m1f6bv.css';
import '../../css/j/j1jcq5b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="urz-4cihd"/><path clip-rule="evenodd" class="z77m1f6bv"/><path class="j1jcq5b8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-scan-fill" {...props}></Icon>
