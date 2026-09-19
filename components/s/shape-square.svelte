<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbtys5b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbtys5b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:shape-square" {...props}></Icon>
