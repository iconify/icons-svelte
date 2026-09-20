<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4z0gdu1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4z0gdu1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star5-filled" {...props}></Icon>
