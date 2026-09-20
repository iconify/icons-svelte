<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9w3hdc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9w3hdc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-4g" {...props}></Icon>
