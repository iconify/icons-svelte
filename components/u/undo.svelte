<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skh9tab_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-2};
const content = `<path class="skh9tab_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:undo" {...props}></Icon>
