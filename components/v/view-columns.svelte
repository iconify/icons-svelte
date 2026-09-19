<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-jp0obey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-jp0obey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:view-columns" {...props}></Icon>
