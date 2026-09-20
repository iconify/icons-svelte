<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un2jr5b5x.css';
import '../../css/u/u6c0nebia.css';
import '../../css/m/m6vv16rhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un2jr5b5x"/><path class="u6c0nebia"/><path class="m6vv16rhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:signal-alt-3" {...props}></Icon>
