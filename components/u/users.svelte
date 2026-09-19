<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv90j7b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv90j7b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:users" {...props}></Icon>
