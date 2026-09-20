<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slij-3bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slij-3bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:subtask" {...props}></Icon>
