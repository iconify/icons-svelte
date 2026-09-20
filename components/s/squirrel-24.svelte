<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq3i7sb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq3i7sb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:squirrel-24" {...props}></Icon>
