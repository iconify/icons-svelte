<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nns0k0bcj.css';
import '../../css/g/g7mt9ybuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="nns0k0bcj"/><path clip-rule="evenodd" class="g7mt9ybuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search-2" {...props}></Icon>
