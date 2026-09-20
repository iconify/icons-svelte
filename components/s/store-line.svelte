<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojbjifbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojbjifbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:store-line" {...props}></Icon>
