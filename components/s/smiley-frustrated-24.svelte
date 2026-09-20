<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbrkzh8sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbrkzh8sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-frustrated-24" {...props}></Icon>
