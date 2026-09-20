<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dirlafbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dirlafbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upload-cloud-2-fill" {...props}></Icon>
