<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2c_bsglq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r2c_bsglq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:usersad" {...props}></Icon>
