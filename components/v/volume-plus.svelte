<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td913yb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td913yb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:volume-plus" {...props}></Icon>
