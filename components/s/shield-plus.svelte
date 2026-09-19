<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp5hu8pgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp5hu8pgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shield-plus" {...props}></Icon>
