<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv57_8jja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv57_8jja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-alert" {...props}></Icon>
