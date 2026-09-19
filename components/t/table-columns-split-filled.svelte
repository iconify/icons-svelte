<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6a_8ccch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6a_8ccch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-columns-split-filled" {...props}></Icon>
