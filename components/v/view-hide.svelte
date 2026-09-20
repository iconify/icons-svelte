<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cpwfl8z9j.css';
import '../../css/k/k7umfem1u.css';
import '../../css/b/b2jj2nm-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cpwfl8z9j"/><path clip-rule="evenodd" class="k7umfem1u"/><path class="b2jj2nm-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:view-hide" {...props}></Icon>
