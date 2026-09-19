<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz711pbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz711pbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:text-align-left" {...props}></Icon>
