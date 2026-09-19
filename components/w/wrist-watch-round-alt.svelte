<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j531q7orm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j531q7orm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-round-alt" {...props}></Icon>
