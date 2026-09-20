<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gapzs4b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gapzs4b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thumbs-down-3" {...props}></Icon>
