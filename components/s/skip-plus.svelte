<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxrkksz8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxrkksz8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-plus" {...props}></Icon>
