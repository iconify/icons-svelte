<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd_t_2b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd_t_2b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:search-small" {...props}></Icon>
