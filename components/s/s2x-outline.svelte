<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfxiq65yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xfxiq65yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:s2x-outline" {...props}></Icon>
