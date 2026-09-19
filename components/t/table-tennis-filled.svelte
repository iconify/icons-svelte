<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6etw8bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6etw8bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-tennis-filled" {...props}></Icon>
