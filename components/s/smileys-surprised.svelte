<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoyldubjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zoyldubjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:smileys-surprised" {...props}></Icon>
