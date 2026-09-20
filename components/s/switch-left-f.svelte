<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j91bif6wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="j91bif6wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:switch-left-f" {...props}></Icon>
