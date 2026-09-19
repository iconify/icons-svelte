<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpfv3y81q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpfv3y81q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:view-column" {...props}></Icon>
