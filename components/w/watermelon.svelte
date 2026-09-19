<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mesj8d27e.css';
import '../../css/d/dfew9rbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mesj8d27e"/><path class="dfew9rbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:watermelon" {...props}></Icon>
