<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuqmktwbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuqmktwbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:swr" {...props}></Icon>
