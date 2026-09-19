<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca7z5h1rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7z5h1rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:start-record" {...props}></Icon>
