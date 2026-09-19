<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imw6l2u6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imw6l2u6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:settings-alt-filled" {...props}></Icon>
