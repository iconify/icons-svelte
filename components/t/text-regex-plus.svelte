<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyvraz85q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyvraz85q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:text-regex-plus" {...props}></Icon>
