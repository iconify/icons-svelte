<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpf9e0yer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpf9e0yer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:youtube-fill" {...props}></Icon>
