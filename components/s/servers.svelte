<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijy3k1pdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijy3k1pdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:servers" {...props}></Icon>
