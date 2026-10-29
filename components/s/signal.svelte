<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3t67bbhr.css';
import '../../css/v/v3utk9btu.css';
import '../../css/a/aao78ab3u.css';
import '../../css/a/a33y997-f.css';
import '../../css/j/jl36678xc.css';
import '../../css/g/gr9c55nys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3t67bbhr wm-shadow"/><path class="v3utk9btu wm-k"/><path class="aao78ab3u wm-k"/><path class="a33y997-f wm-k"/><path class="jl36678xc wm-k"/><path class="gr9c55nys wm-shine"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:signal" {...props}></Icon>
