<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygki8j0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygki8j0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sunset-solid" {...props}></Icon>
