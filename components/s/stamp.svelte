<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs1ds98ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs1ds98ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:stamp" {...props}></Icon>
