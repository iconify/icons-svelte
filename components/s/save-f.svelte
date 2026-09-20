<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_grw2bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="w_grw2bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:save-f" {...props}></Icon>
