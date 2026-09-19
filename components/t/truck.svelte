<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvarxe4oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvarxe4oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:truck" {...props}></Icon>
