<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an9moxdyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an9moxdyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trouser-line" {...props}></Icon>
