<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrmierbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrmierbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:swords" {...props}></Icon>
