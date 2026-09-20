<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_dlebfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9_dlebfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stairs-up" {...props}></Icon>
