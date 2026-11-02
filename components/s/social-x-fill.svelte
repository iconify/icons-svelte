<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brjq0bcwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brjq0bcwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:social-x-fill" {...props}></Icon>
