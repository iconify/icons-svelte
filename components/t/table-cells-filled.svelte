<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk91yiz0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk91yiz0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-cells-filled" {...props}></Icon>
