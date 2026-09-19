<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu_qqx5qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_qqx5qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trend-down" {...props}></Icon>
