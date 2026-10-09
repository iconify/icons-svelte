<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4h6c1fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hw4h6c1fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:users-20-bold" {...props}></Icon>
