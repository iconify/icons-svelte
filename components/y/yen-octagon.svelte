<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbn3z8r9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbn3z8r9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-octagon" {...props}></Icon>
