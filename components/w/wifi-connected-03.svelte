<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe5lveblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe5lveblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-connected-03" {...props}></Icon>
