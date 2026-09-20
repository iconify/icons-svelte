<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls9fy_b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ls9fy_b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:swerve-filled" {...props}></Icon>
