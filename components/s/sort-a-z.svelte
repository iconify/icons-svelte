<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4pekuvlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4pekuvlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:sort-a-z" {...props}></Icon>
