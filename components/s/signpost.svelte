<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apz4wh5li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apz4wh5li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:signpost" {...props}></Icon>
