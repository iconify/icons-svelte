<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwwgz8biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwwgz8biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vimeo-logo-block" {...props}></Icon>
