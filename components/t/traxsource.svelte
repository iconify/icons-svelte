<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-6yrobrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-6yrobrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:traxsource" {...props}></Icon>
