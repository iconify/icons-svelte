<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clnl6s1aj.css';
import '../../css/w/whz9jobil.css';
import '../../css/u/u65oy1y8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clnl6s1aj"/><rect class="whz9jobil"/><rect class="u65oy1y8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-distribute-top-filled" {...props}></Icon>
