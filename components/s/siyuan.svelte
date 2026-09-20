<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ickqhbbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ickqhbbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:siyuan" {...props}></Icon>
