<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgtybey6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgtybey6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:type-text" {...props}></Icon>
