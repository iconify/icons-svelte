<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho-7w3yfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho-7w3yfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-list-round" {...props}></Icon>
