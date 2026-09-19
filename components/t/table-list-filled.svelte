<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq8_w3bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8_w3bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-list-filled" {...props}></Icon>
