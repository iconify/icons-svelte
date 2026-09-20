<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy9zbe3mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy9zbe3mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:ticket-alt-fill" {...props}></Icon>
