<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecpwv1b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecpwv1b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thumbs-up" {...props}></Icon>
