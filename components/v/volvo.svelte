<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feb6apbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feb6apbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:volvo" {...props}></Icon>
