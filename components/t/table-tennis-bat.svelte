<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx5l_hbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx5l_hbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-tennis-bat" {...props}></Icon>
