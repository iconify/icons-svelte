<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h34zihb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h34zihb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:virgin" {...props}></Icon>
