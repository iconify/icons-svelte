<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0i-_6b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d0i-_6b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:user-circle" {...props}></Icon>
