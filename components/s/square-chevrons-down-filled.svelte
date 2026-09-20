<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9q5y8bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9q5y8bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-chevrons-down-filled" {...props}></Icon>
