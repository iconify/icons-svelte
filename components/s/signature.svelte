<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc24mdbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc24mdbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:signature" {...props}></Icon>
