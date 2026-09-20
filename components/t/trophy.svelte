<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_y4od_0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_y4od_0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:trophy" {...props}></Icon>
