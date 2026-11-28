<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvre9sbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary pvre9sbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-pisces-duotone" {...props}></Icon>
