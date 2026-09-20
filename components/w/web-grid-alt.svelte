<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhg7x8ycq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhg7x8ycq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:web-grid-alt" {...props}></Icon>
