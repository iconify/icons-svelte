<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5sthicge.css';
import '../../css/g/gr9tg1wsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5sthicge"/><path class="gr9tg1wsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:theo" {...props}></Icon>
