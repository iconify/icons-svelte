<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo_l22ipq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_l22ipq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:wrap-text" {...props}></Icon>
