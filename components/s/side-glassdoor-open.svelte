<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9wp55b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9wp55b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:side-glassdoor-open" {...props}></Icon>
