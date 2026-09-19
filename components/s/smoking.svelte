<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wczi_xsit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wczi_xsit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smoking" {...props}></Icon>
