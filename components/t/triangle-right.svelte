<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vazj0kb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vazj0kb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle-right" {...props}></Icon>
