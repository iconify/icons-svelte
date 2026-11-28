<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk3ftabft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk3ftabft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:settings" {...props}></Icon>
