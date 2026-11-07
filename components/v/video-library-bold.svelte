<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3_gtob6t.css';
import '../../css/b/bz0qnvbjd.css';
import '../../css/x/xc6fu6b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="bz0qnvbjd"/><path clip-rule="evenodd" class="xc6fu6b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-library-bold" {...props}></Icon>
