<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4-i83b6x.css';
import '../../css/c/c8yw7loqa.css';
import '../../css/y/yi_r72bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-i83b6x"/><path class="c8yw7loqa"/><path class="yi_r72bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:wrap-text" {...props}></Icon>
