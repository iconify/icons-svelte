<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gplo0fbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gplo0fbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:table-fill" {...props}></Icon>
