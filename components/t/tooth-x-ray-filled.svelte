<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb7iodb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bb7iodb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-x-ray-filled" {...props}></Icon>
