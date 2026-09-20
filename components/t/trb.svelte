<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1pcenfhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1pcenfhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:trb" {...props}></Icon>
