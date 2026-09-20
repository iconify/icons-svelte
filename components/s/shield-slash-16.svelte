<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2qg43z_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m2qg43z_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-slash-16" {...props}></Icon>
