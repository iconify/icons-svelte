<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unl-a7bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unl-a7bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ufc" {...props}></Icon>
