<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arj-2gbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arj-2gbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:van" {...props}></Icon>
