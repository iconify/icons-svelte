<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flcec9i_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flcec9i_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wine" {...props}></Icon>
