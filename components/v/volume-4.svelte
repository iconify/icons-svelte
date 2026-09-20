<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z68h5ubme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z68h5ubme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:volume-4" {...props}></Icon>
