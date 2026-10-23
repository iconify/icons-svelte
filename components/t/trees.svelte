<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clquyccsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clquyccsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trees" {...props}></Icon>
