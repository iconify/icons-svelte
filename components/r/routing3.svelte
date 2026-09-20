<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-q6ykb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l-q6ykb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:routing3" {...props}></Icon>
