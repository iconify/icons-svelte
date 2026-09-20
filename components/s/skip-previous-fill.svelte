<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z96m-mn-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z96m-mn-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skip-previous-fill" {...props}></Icon>
