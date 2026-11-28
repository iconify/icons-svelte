<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6c3c4-rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6c3c4-rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:school-clock" {...props}></Icon>
