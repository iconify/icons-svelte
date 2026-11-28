<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qypqtym9h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bs3qkuyvu.css';
import '../../css/p/p0z9gxbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qypqtym9h secondary"/><g class="dt0cm9dhy primary"><path class="bs3qkuyvu"/><path class="p0z9gxbvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wand-duo" {...props}></Icon>
