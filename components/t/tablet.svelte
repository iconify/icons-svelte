<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7c9d3plm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="u7c9d3plm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tablet" {...props}></Icon>
