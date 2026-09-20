<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x09f78b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x09f78b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:trash" {...props}></Icon>
