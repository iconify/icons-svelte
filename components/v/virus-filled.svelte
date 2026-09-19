<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur9dyaefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ur9dyaefx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:virus-filled" {...props}></Icon>
