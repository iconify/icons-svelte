<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6dbe6byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6dbe6byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-r-filled" {...props}></Icon>
