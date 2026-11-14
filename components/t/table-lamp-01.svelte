<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr-9cvk0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr-9cvk0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-lamp-01" {...props}></Icon>
