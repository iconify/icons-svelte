<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9h3i4b2f.css';
import '../../css/a/a7grcu7de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9h3i4b2f"/><path class="a7grcu7de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:video-file-duotone" {...props}></Icon>
