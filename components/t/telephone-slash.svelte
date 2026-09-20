<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktc0rob3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktc0rob3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-slash" {...props}></Icon>
