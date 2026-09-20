<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8lxn4b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8lxn4b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:strikethrough-fill" {...props}></Icon>
