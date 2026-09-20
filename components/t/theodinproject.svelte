<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu797ubab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu797ubab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:theodinproject" {...props}></Icon>
