<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5r444b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5r444b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:temperature-fill" {...props}></Icon>
