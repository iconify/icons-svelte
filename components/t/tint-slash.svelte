<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhf_bmb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bhf_bmb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tint-slash" {...props}></Icon>
