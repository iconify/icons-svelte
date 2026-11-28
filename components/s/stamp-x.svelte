<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im4z9ha3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im4z9ha3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:stamp-x" {...props}></Icon>
