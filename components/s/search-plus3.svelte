<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf5j1qb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf5j1qb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-plus3" {...props}></Icon>
