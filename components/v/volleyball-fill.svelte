<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqld04bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqld04bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volleyball-fill" {...props}></Icon>
