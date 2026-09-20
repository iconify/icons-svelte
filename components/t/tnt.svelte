<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auw7t_nln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auw7t_nln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tnt" {...props}></Icon>
