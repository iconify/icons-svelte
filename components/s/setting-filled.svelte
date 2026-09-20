<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktz_dipcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktz_dipcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting-filled" {...props}></Icon>
