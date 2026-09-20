<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vheocit6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vheocit6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trash-can-light" {...props}></Icon>
