<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bph8-725u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bph8-725u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-6g" {...props}></Icon>
