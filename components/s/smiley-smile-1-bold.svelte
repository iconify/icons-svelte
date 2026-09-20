<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7-2vjb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7-2vjb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-smile-1-bold" {...props}></Icon>
