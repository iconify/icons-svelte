<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtm0kz49x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtm0kz49x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webpack" {...props}></Icon>
