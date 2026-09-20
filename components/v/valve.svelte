<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4q1gquzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4q1gquzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:valve" {...props}></Icon>
