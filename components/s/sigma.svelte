<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioboqwblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioboqwblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sigma" {...props}></Icon>
