<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaapcj7my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaapcj7my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trend-up" {...props}></Icon>
