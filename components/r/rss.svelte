<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poj4ron-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poj4ron-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rss" {...props}></Icon>
