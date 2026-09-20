<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-n7qqbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-n7qqbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spotlight" {...props}></Icon>
