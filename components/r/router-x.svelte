<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_4q0l3ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_4q0l3ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:router-x" {...props}></Icon>
