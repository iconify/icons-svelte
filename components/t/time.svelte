<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0m8wdw9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0m8wdw9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:time" {...props}></Icon>
