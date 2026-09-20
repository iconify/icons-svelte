<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na-hv6n7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na-hv6n7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-plus" {...props}></Icon>
