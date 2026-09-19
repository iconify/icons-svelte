<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw15_svps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw15_svps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:seat-filled" {...props}></Icon>
