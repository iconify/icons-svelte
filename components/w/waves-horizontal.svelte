<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3n7f0bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3n7f0bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:waves-horizontal" {...props}></Icon>
