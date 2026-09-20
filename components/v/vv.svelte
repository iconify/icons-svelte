<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuon0ob1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuon0ob1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vv" {...props}></Icon>
