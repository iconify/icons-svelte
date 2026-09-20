<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giizjpb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giizjpb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-descending-2-filled" {...props}></Icon>
