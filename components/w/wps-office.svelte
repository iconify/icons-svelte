<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lix6-_buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lix6-_buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wps-office" {...props}></Icon>
