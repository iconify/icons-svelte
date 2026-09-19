<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je4pjdbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je4pjdbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:thunder" {...props}></Icon>
