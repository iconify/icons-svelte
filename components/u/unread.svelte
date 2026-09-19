<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtjxobj7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjxobj7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:unread" {...props}></Icon>
