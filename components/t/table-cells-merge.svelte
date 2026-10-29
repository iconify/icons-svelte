<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uryvlvbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uryvlvbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:table-cells-merge" {...props}></Icon>
