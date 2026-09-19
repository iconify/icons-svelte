<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndvb1fb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndvb1fb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-x-ray" {...props}></Icon>
