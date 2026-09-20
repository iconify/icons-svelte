<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr6qntbff.css';
import '../../css/y/y6q6mnb3i.css';
import '../../css/r/re7ja8bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr6qntbff"/><path class="y6q6mnb3i"/><path class="re7ja8bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shop-1-filled" {...props}></Icon>
