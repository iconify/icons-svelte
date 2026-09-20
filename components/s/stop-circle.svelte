<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuqt_yb-q.css';
import '../../css/l/ljusak9qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><rect class="ljusak9qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:stop-circle" {...props}></Icon>
