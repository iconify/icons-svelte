<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbrhzbb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbrhzbb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ufi" {...props}></Icon>
